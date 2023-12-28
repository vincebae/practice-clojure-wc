
## Write Your Own wc Tool
Coding challenge from https://codingchallenges.fyi/challenges/challenge-wc


#### Requirements

* clojure
* babashka

#### Usage

`$ ./wc [OPTION]... [FILE]...`

When no file is specified, read from stdio.
Linux pipe can be used like

`$ cat [FILE] | ./wc`


#### Run Tests

`$ bb test`

