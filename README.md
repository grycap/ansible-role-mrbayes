[![License](https://img.shields.io/badge/license-Apache%202-blue.svg)](https://www.apache.org/licenses/LICENSE-2.0)
[![Build Status](https://travis-ci.org/grycap/ansible-role-mrbayes.svg?branch=master)](https://travis-ci.org/grycap/ansible-role-mrbayes)

MrBayes Role
===================

Ansible Role to install MrBayes software (recipe for EC3). MrBayes (http://mrbayes.sourceforge.net/) is a program for Bayesian inference and model choice across a wide range of phylogenetic and evolutionary models. MrBayes uses Markov chain Monte Carlo (MCMC) methods to estimate the posterior distribution of model parameters.

Example Playbook
----------------
```
  - hosts: server
  roles:
  - { role: 'grycap.mrbayes'}
```
```
  - hosts: client
  roles:
  - { role: 'grycap.mrbayes'}
```

Contributing to the role
========================
In order to keep the code clean, pushing changes to the master branch has been disabled. If you want to contribute, you have to create a branch, upload your changes and then create a pull request.  
Thanks
