# Cache-line aware data structures

## Jitter

Jitter is the variance in time around operations that are notionally have constant time expectations.

For example:

 - Wall clock on a system. System wall clock has a 'tick' of which the unit to measure this will have some associated variance. Wall clock tick might be, say, 1 microsecond, but there will be associated 'jitter of +/- 1.5 microseconds. Clock's accuracy may be considered better over longer times periods, but each tick has some jitter with it.
 -  Accessing memory linearly in a system has constant access time, until a page fault is hit. Page fault can introduce delay. Results in a constant time operation but with predictable jitter.
 - 
