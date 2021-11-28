---
description: How to work, organize, describe and deal with variables.
cover: ../.gitbook/assets/avenue-2215317_1280.jpg
coverY: 0
---

# 🤓 Variables

## Overview

Variables are one of the cornerstones for Terraform, they are a large portion of the interface between those using the module and those who wrote it.

## Structure and Organization

Input variables have a few properties which can be declared in a flexible way, but to keep your `variables.tf` file readable, there are a few patterns that should be followed, such as keeping the same order in the declaration of your variable's properties, the order suggested here is:&#x20;

* `name` - Required to be the first property
* `description` - Brief explanation of the variable's role
* `type` - Variable's accepted type (e.g. string, number, bool)
* `validation` - Validation constraints for the value
* `sensitive` - Used to supress secrets in the CLI's output

### Name

### Description

### Type

### Validation

### Sensitive
