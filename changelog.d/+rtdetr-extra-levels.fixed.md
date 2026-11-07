`RTDETRHead` builds the stride-2 projections for feature levels beyond the backbone maps, instead of raising `IndexError`. A call with more maps than `num_levels` reports both counts.
