# Raft's election

raftnode.py is implemented for a single RAFT node.

This code ensures that client can query your RAFT nodes to 
determine which one of them, if any, is a leader.

The election will automatically begin when there is no leader
and will end if the leader has been elected.
