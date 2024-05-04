# Lab 5 - Starter

## Names/Lab members
- Andrew Pegg

## links
[epxose part 1](https://andrewcomputsci2019.github.io/Lab5_Starter/expose) \
[explore part 2](https://andrewcomputsci2019.github.io/Lab5_Starter/explore)

## Part 3
### Check your understanding
- 1) No, making a unit test for this would not make sense, this is more of an integration test, verifying that a process/component can interact with another process or feature. Unit testing if a user could write to another in a messaging system would not really be a unit test as its scope quickly relies on other parts of the code base outside the unit scope, as noted above integration/system test would make more sense as we want to see the interplay of multiple components of the messaging system and the necessary other systems like a relay server etc.
- 2) Yes, using a unit test to verify the max message length feature makes sense as the test scope can be accomplished within the single part of the code base handling the message length checking. This test would not rely on other features within the code base, making it a perfect candidate for unit testing.
