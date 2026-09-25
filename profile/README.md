# Knave Desktop Environment

<p align="center">
  <img src="Knave-Color-Light.svg#gh-light-mode-only" alt="Knave logo" width="144" />
  <img src="Knave-Color-Dark.svg#gh-dark-mode-only" alt="Knave logo" width="144" />
</p>

<p align="center"><strong>A tiling-first desktop environment for Linux.</strong></p>

Knave is a desktop environment built around tiled windows and workspaces. It treats window layout as a first-class part of the desktop and uses workspaces to keep different tasks organized. The goal is a desktop that feels coherent by default while still being meaningfully customizable.

## How Knave works

- **Tiling is the foundation.** The workspace overview preserves the arrangement of tiled windows, so users can recognize and choose a window without losing the layout.
- **Workspaces provide context.** Each workspace keeps its own windows and arrangement.
- **Minimized windows stay connected.** A minimized window leaves the tile layout but remains associated with its workspace. The overview shows minimized windows as icons or cards.
- **Activation should be deliberate.** Explicitly choosing a window should take the user to it. Background requests should not unexpectedly take focus.

## Overview

The initial overview focuses on the current workspace. It presents that workspace's tiled windows in their existing arrangement and makes minimized windows available as icons or cards.

A later overview mode may show all workspaces that contain windows. The first implementation focuses on the current workspace.
