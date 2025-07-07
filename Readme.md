# Rules for Pharo

This repository contains material around rules for Pharo.


The mailing-list is lse-mada-rules@inria.fr.
Just ask if you want to join. 


## Possible topics

### Automatic Profiles for Rules

In Pharo there is a large set of quality rules. You can see them using the quality browser. One of the problem is that all the rules are run independently of the
developer level. The goal of this master is to define levels for newbies, experts and others and to assess which rules should be executed.

- We can first attached meta information to the rules and build groups from them.
- In a second step, we can  learn from the previously failing rules the profile of the users and
eliminate or add some specific rules to its profile.
- Identifying rules that capture the newbies mistakes.

### More domain specific rules

The goal of this internship is to do define more specific rules. 

We can have rules for:
- Refactoring drivers (for example they should not call generateChanges) See https://github.com/pharo-project/reEngine
- The pharo git repository list possible rule improvement (with the tag project: rules) https://github.com/pharo-project/pharo/issues?q=is%3Aissue%20state%3Aopen%20rule%20label%3A%22Project%3A%20Rules%22
- A call to the community to ask for rules that people would like to get.
- The paper Rule-based Assessment of Test Quality provides some possible rules.