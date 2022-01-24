# Macchina
<div align="center">
<h1>macchina</h1>

Fast, minimal and customizable system information frontend.

Linux • macOS • Windows • NetBSD • FreeBSD • OpenWrt • Android

<a href="https://matrix.to/#/#macchina:matrix.org">
    <img src="https://img.shields.io/matrix/macchina:matrix.org" alt="Matrix" />
</a>

<a href="https://crates.io/crates/macchina">
    <img src="https://img.shields.io/crates/v/macchina?label=Version" alt="Version" />
</a>

<a href="https://crates.io/crates/macchina">
    <img src="https://img.shields.io/crates/d/macchina?label=Downloads" alt="Downloads" />
</a>

<a href="https://github.com/Macchina-CLI/macchina/actions">
   <img src="https://github.com/Macchina-CLI/macchina/actions/workflows/macchina.yml/badge.svg" alt="CI">
</a>

<img src="preview/Screenshot.png" alt="Preview" />

</div>

## About

_macchina_ lets you view system information, like your kernel version, uptime,
memory usage, processor load and much more. _macchina_ is **basic** by default
and **extensible** by design.

If you're interested in the library _macchina_ uses to fetch system
information, have a look at
[libmacchina]; fetching-related
issues should be filed on that repository.

## Benchmarks <a name="benchmarks"></a>

Check out the [benchmarks wiki page](https://github.com/Macchina-CLI/macchina/wiki/Benchmarks).

## Features

### Themes

_macchina_ has a theming system which you can use to customize pretty much any
visual aspect of the program. Themes live **outside** the configuration file,
so you can create a bunch of them and switch between them at any time.

Why are they separate?

- **Modularity** — themes are an engine of their own, and their sole purpose is
  to provide an interface that allows for the modification of _macchina's_
  visual components. It makes sense to separate them from the main
  configuration file.

- **Portability** — sure, the configuration file is shareable, but what if you
  wanted to share the look of _your macchina_ and not its behavior? What if you
  wanted to switch between dozens of themes that you very carefully designed?
  The way we handle customization answers this need.

Learn how to [make your own](#customization).

### Doctor

In the event of fetching failures, which can occur for various reasons, the
`--doctor` flag that can tell you why that might be happening.

## Configuration

See the [configuration wiki page](https://github.com/Macchina-CLI/macchina/wiki/Configuration).

## Customization

Have a look at the [customization wiki page](https://github.com/Macchina-CLI/macchina/wiki/Customization).

## Installation

[![Packaging status](https://repology.org/badge/vertical-allrepos/macchina.svg)](https://repology.org/project/macchina/versions)

Check out the [installation wiki
page](https://github.com/Macchina-CLI/macchina/wiki/Installation).

[Prebuilt binaries](https://github.com/grtcdr/macchina/releases) are also
provided with every release, feel free to use them.

