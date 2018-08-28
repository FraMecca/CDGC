# Milestones for the CDGC

### Month 1 (ends on October 1st)
After reaching an agreement on a test suite with my mentor (including both the druntime test cases and real programs), I'll start adapting the current GC in order to include the concurrent fork() based behaviour.
Before the deadline, I will present the successfull test cases and if possible, some early benchmarks.

### Month 2 (ends on November 1st)
I'll continue working and fixing memory related bug. At this point I should focus on passing every test bfore continuing to the next milestone.

### Month 3 (ends on December 1st)
profiling and benchmarking the new GC while discussing and documenting real world scenarios where a fork() based concurrent GC outperforms the current GC

### Final submission (January 1st)
the project should terminate with a PR to the DRuntime that presents the work and opens a discussion.
