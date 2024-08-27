AreaRegen Plugin
=================

## Description

The AreaRegen plugin is a simple and easy-to-use plugin that allows you to regenerate blocks that have been exploded by TNT. This plugin works with WorldGuard if you want to restrict the regeneration to specific regions, and it can also work on the entire world if WorldGuard is not installed.

## Features

- ### Per-world regeneration time and delay
- ### Per-WorldGuard region regeneration time and delay
- ### Option to regenerate blocks exploded by TNT
- ### Option to regenerate blocks in the entire world or in specific WorldGuard regions
- ### Easy-to-use configuration file

## Installation

### 1. Download the latest version of the AreaRegen plugin
[![GitHub Release](https://img.shields.io/github/release/Mardssss/AreaRegen.svg)](https://github.com/Mardssss/AreaRegen/releases)
### 2. Place the downloaded JAR file in your Minecraft server's `plugins` directory.
### 3. Restart your Minecraft server.
### 4. Configure the plugin using the `config.yml` file in the plugin's directory.

## Usage

To use the AreaRegen plugin, simply place TNT in the area you want to regenerate, and then detonate it. The plugin will automatically regenerate the blocks in the area after the configured delay.

If you have WorldGuard installed, you can restrict the regeneration to specific regions by using the `regions` configuration option in the `config.yml` file.

## Configuration

The AreaRegen plugin comes with a `config.yml` file that allows you to configure various aspects of the plugin. Here are the available configuration options:

### `worlds`: A list of worlds where the plugin should be active.
### `regen-time`: The delay in ticks between block regeneration.
### `delay`: The time in ticks before the task starts.
### `regions`: A list of WorldGuard regions where the regeneration should be active.

## Support

If you find any bug in the AreaRegen plugin, please open an issue
[![GitHub Issues](https://img.shields.io/github/issues/Mardssss/AreaRegen.svg)](https://github.com/Mardssss/AreaRegen/issues).
