# RiceChecks: "Regex" Example

This repo is a demonstration project for the [RiceChecks](https://github.com/RiceComp215-Staff/RiceChecks/) Java autograder.

In this hypothetical project, students are asked to implement several regular expressions;
their work is tested using JUnit5's [TestFactory](https://junit.org/junit5/docs/5.4.0/api/org/junit/jupiter/api/TestFactory.html),
which has a list of examples for each regex that should be accepted and another list
of examples that should be rejected by the regex.

The initial state of this repository has all tests passing. Feel free
to introduce bugs to the student assignment and see how RiceChecks responds.

## Gitpod

Here's a link that will drop you into the Gitpod web-based IDE using
this codebase:
- https://gitpod.io/github.com/RiceComp215-Staff/RiceChecks-RegexExample

(You can replace this URL with any public GitHub repository with
`gitpod.io` before the usual `github.com`.)

From the Gitpod terminal shell, run `./gradlew autograder`. 

## GitHub Actions                                                                                                                        
                                                                                                                                         
If you're a beta-tester for GitHub Actions, this repository is configured to run the                                                     
autograder as a GitHub Action on every push.                                                                                             
You can see the results of the autograder by clicking the                                                                                
"Commits" tab. Try introducing bugs, committing and pushing, to see how RiceChecks                                                       
responds.  
