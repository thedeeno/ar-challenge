ar-challenge
============

Problem set for training AR

Goal
====

Model a graph with active record models.

Something that looks like:

node - link - node - link - node
node -  /

Requirements:
 * A link has upstream and downstream nodes
 * A node has an upstream and downstream link
 * A node should have a list of the closest upstream and downstream nodes

Notes:

The models are created and empty migrations already setup. Fill out
the migrations and setup the associations. 

When done, create a simple program to exercise the solution in the rake task under
`lib/tasks/program.rake`. Run the task with `rake program:run`
