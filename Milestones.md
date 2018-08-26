# Milestones for the CDGC

### Month 1 (ends on October 1st)
porting the D1 implementation of the GC to D2 and adapt it to the [gc interface](https://github.com/dlang/druntime/blob/master/src/gc/gcinterface.d)

### Month 2 (ends on November 1st)
testing the GC with a test suite and with the most famous Dlang codebases (such as Mir and Vibe.d), along with bugfixing and optimizations

### Month 3 (ends on December 1st)
profiling and benchmarking the new GC while discussing and documenting real world scenarios where a fork() based concurrent GC outperforms the current GC

### Final submission (January 1st)
the project should terminate with a PR to the DRuntime that presents the work and opens a discussion.
