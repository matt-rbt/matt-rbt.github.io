---
layout: page
title: Mirte Lab Clean
description: Autonomous laboratory cleanup robot — ROS2, Nav2, behaviour trees
img: assets/img/projects/mirte_lab_clean.gif
importance: 1
category: robotics
github: https://github.com/matt-rbt/Mirte_Lab_Clean
---

An autonomous mobile manipulator designed to detect and clear lab clutter without human intervention. Built on the **MIRTE Master** platform as a group project at TU Delft.

## Autonomy & navigation

The robot navigates unknown lab environments using **Nav2** with SLAM Toolbox. A **coverage path planner** generates goals to explore the space, while a **behaviour tree** (py_trees_ros) orchestrates the full mission loop, detecting objects, and triggering arm actions in sequence.

My role:
- Costmap inflation tuning to prevent goal infeasibility near obstacles
- TF timestamp synchronisation between the MIRTE base and an Orbbec Astra depth camera
- Robust behaviour tree design handling navigation retries and failure recovery

## Tech stack

`ROS2 Humble` `Nav2` `SLAM Toolbox` `py_trees_ros` `MoveIt2` `Python` `Orbbec Astra`

## Status

🚧 In progress — navigation and manipulation subsystems operational; full integration ongoing.

[Read more](https://matt-rbt.github.io/Lab-Cleanup-Robot-using-the-Mirte-Master-Platform/){: .btn}
