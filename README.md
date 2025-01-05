# NKlandscape_TOMcompetition

This "Better Credit" search algorithm was put together for the TOM NK landscape competition, but it reflects some ideas I've had for a while for an epistemic network model.

This algorithm is inspired by the “credit economy” as it is discussed in social epistemology. Initial searches aim to produce configurations that are significantly different from prior configurations (reflecting researchers being motivated to produce original ideas for which they will be credited). This promotes transient diversity. Then, after this initial phase, local searches are performed on promising configurations. These searches start from a randomly selected configuration chosen from a set of top performers (inspired by Wu’s Better than Best model). When a local search produces a configuration already investigated, I found a measurable improvement by doing a new random selection rather than merely doing a new local search. I believe that, in part, this improvement is due to configurations that have already been frequently investigated being more likely to produce duplicates. I.e., doing a new random selection increases transient diversity in virtue of less investigated configurations being less likely to produce a duplicate and consequently more likely to yield the choice configuration.
