# CLOUD-PROJECT
Problem statement->
Given in the input a data replication policy that comprises of three strategies: (a) instant replication, (b)
delayed replication, (c) no replication, and given a data row labelled with one of the three
strategies above, implement data replication. Test with synthetic data with randomly generated
labels. Implement this using Docker data containers.

# First of all we installed a Docker data container with centos image.
# Then we created a bash script file named "Random" for creating a random file with labeled(extension) hot , warm ,cold.
# We created a three data container container1,container2,container3 .
# we created a bash script for replicating named " Replicate " eg:- for hot labeled data we replicate it into container1 and          container2  instantly and for warm data we replicate it into container 3 with some delay and for cold data we never replicated data.
