# 3D-motion-planning

Mobile robots are becoming more and more widely
used in industry and life, so the navigation of mobile robots has
become an urgent problem to be solved.This project deals with
the path planning of mobile robots to avoid static obstacles using
improved Artificial Potential Field method. The classical Artificial
Potential Field (APF) method consists of assigning an attractive
artificial potential field to the destination point that attracts the
robot, and a repelling artificial potential field to the obstacles
that repel the robot. We use modified APF which redefines the
repulsive and attractive potential fields and add correction factors
to them to avoid the inherent problems of the classical APF such
as the local minima and the inaccessibility of the targe

The basic idea of APF method assumes that robot as a point
moves in an abstract artificial force field. The artificial field
in environment is composed of attractive field of target and
repulsive field of obstacles. Attractive field is produce by target
and direct to target point, while repulsive field is the synthesis
repulsive field of different obstacles and the direction of the
synthesis repulsive field is away from obstacles. Therefore, the
potential function is the APF of robot which is defined as the
resultant of attractive field and repulsive field. Robot controls
its movement toward the target point along the direction of
APF. Under the method of APF, robot could find a collision-
free path by searching the route along the decline direction
of potential function. The negative gradient of APF is defined
as artificial force which is the steepest descent direction for
guiding robot to target point. Attractive force is the negative
gradient of attractive field, and repulsive force is the negative
gradient of repulsive field. 

## Results


https://user-images.githubusercontent.com/94932358/168962925-84a9b3e3-00c0-4b68-9652-7ed3237ce979.mp4




![path 2d](https://user-images.githubusercontent.com/94932358/168961622-f678100c-88e8-4c94-aa72-e4fe873e0c17.png)
![3d view](https://user-images.githubusercontent.com/94932358/168961674-7a1e0bbf-4480-498c-85b1-66659574b9b5.png)
