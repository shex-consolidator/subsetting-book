Types of subsets
===============
With subsetting of RDF graphs is meant the creation of a subset of a (large) RDF graph. The subset can be created in different ways. In this chapter we will describe the following types of subsets:
* Open subsets
* Closed subsets
* Federated subsets
* Combined subsets

## Open subsets
An open subset is a subset that was generated using a subset query that only partly describes the resulting subset. The subset query is not complete, as it does not describe all the triples that are part of the subset. As such, the subset query does not describe the subset completely. The subset query is open. For example the following subset query describes a subset that consists of x triple patterns, yet the resulting subset conforms to more than x patterns.

## Closed subsets
A closed subset is a subset that was generated using a subset query that fully describes the resulting subset. The subset query is complete, as it describes all the triples that are part of the subset. As such, the subset query describes the subset completely. The subset query is closed. For example the following subset query describes a subset that consists of x triple patterns, and the resulting subset conforms to exactly x patterns.

## Federated subsets
A federated subset is a subset that was generated using a subset query that describes the resulting subset using a combination of triple patterns and federated triple patterns. A federated query can be either open or closed. 

## Combined subsets
A combined subset is a subset that was generated using various subset queries, that were combined into a single subset. A combined subset can be combined from either open, closed, or both subset queries.