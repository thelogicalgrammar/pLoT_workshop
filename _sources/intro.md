# Introduction

This is the material for Fausto Carcassi's one-day workshop on the probabilistic Language of Thought (pLoT).
This course consists of four short modules: two in the morning, two in the afternoon. We'll start from scratch and build up to modelling category learning in a pLoT with Bayesian learning algorithms.

Some of the course uses [Steven Piantadosi](http://colala.berkeley.edu/people/piantadosi/)'s library [LOTlib3](https://github.com/piantado/LOTlib3). Note that LOTlib3 is slower than other similar inference libraries developed by Piantadosi (e.g. [fleet](https://github.com/piantado/Fleet)). However, we use LOTlib3 for a crucial reasons: it is written entirely in python, which means folks with more python knowledge can easily have a look at what is happening under the hood, and parts of the LOTlib3 code can be explained in class. 

## Structure of the course

The workshop is divided in four sections. The first section focuses on the foundations required to understand the modern approach to the pLoT. The second section contains little introductions to python, to formal grammars, to defining the semantics of a formal grammar, and to approximate Bayesian inference with Markov Chain Monte Carlo algorithms. The third section provides an introduction to the LOTlib3 library. The fourth section focuses on concept learning in a pLoT through a series of case studies.

| Section                                  | Start-end   | 
| ---------------------------------------- |:-----------:|
| Introduction: On the very idea of an LoT | 09:00-10:45 |
| Technical background                     | 11:15-13:00 |
| Lunch                                    | 13:00-14:00 |
| The LOTlib3 library                      | 14:00-15:45 |
| Case studies                             | 16:15-18:00 |

## Table of contents

Here's the table of contents to help you orientate and give you a sense of what's where:

```{tableofcontents}
```

> **_NOTE_** This is very much work in progress, so feel free to send feedback to the email address described by the following string:  `fausto` followed by a dot followed by `carcassi` followed by `@` followed by `gmail.com`. Materials for this course will change and expand as I adapt the course to emerging students' needs.
