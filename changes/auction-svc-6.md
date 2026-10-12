# Drop bids that arrive after tmax instead of queueing them

Late bids are queued and then discarded anyway; dropping them early frees the worker.
