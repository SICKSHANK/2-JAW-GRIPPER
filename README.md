# Gripper Jaw Assembly (SolidWorks)

A small gear driven gripper / jaw that I designed and assembled in SolidWorks.

## What's in here

The main file is `Assem1.SLDASM`. It has 7 different parts and 37 components in total:

| Part | Qty |
|---|---|
| Clamp Support | 8 |
| nuts | 20 |
| PLate | 2 |
| Gripper | 2 |
| Aligner | 2 |
| gear | 2 |
| Motor attachment | 1 |

## How it goes together

Two plates on the top and bottom, with the clamp supports in two rows of 4 (one row on each plate). A gripper jaw sits on each end, and the aligners, gears and nuts are in between. The motor attachment is on the side where the motor mounts.

The assembly is built with Coincident and Concentric mates only.

## Opening it

Keep all the `.SLDPRT` files in the same folder as `Assem1.SLDASM`, otherwise SolidWorks will ask for the missing parts. Saved in SolidWorks 2026.

## Next

Im planning to integrate this model (or another model) into ROS 2 with Gazebo, RViz and MoveIt, so it can be simulated and controlled. I will update this repo once I start on it.
