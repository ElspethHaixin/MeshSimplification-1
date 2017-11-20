# Parallelize Mesh Simplification Algorithm with Pthread and OpenMP

- Bole Chen (bolec@andrew.cmu.edu)
- Haixin Liu (haixinl@andrew.cmu.edu)

## [Proposal](./index)

## Updated Schedule

## Works completed so far

## preliminary results

## Current Issues

## First try to parallelism
Our first try to parallelize the problem is to identify the independent loops within the serial algorithm. These loops can be distributed to many workers in a shared address space fashion. Common implementations include OpenMp and Pthread library.

## Way to final parallelism
