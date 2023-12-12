# Regex Tutorial: Quantifiers 

In this guide, we will learn to understand the role of quantifiers in regular expressions.

## Summary

In this tutorial, we'll focus on the quantifiers used in regular expressionss. These symbols control the repetition of characters, allowing us to create more flexible and advanced search patterns.

## Table of Contents

- [Introduction](#introduction)
- [Basic Quantifiers](#basic-quantifiers)
- [Specific Quantifiers](#specific-quantifiers)
- [Lazy Quantifiers](#lazy-quantifiers)
- [Example](#example)
- [Conclusion](#conclusion)
- [About The Author](#about-the-author)

## Introduction

To understand Quanitifiers we must first understand the basics of regular expressions, or, regex. Regex are a versatile tool for pattern matching in strings. This helps us with things such as validation and advanced find and replace. The use of quantifiers enhances this capability by defining the quanitity or repetition of characters within a pattern. 

## Basic Quantifiers

###  '*' (Zero or more)
The `*` quantifier matches zero or more occurences of the preceding character.

### '+' (One or More)
The `+` quantifier matches one or more occurences of the preceding character.

### '?' (Zero or One)
the `?` quantifier matches zero or one occurance of the preceding character.


## Specific Quantifiers

### '{n}' (Exactly n)
The `n` quantifier matches exactly n occurrences of the preceding character.

### '{n,}' (n or more)
The '{n,}' quantifier matches n or more occurrences of the preceding character.

### '{n,m}' (Between n and m)
The '{n,m}' quantifier matches anything between n and m occurrences.


## Lazy Quantifiers

Lazy quantifiers match the smallest number of occurences needed for an overall match.

## Example

Let's explore a practical example using the regex '/o+/g'

`
const text = "ooo oo o";
const regex = /o+/g;

const matches = text.match(regex);
console.log(matches;)`

In this example, the regex matches one or more consecutive occurrences of 'o' in the given text. So we would see an output of 'ooo' or 'oo' but not 'o'.

## Conclusion

Quantifiers provide flexibility in crafting effective regular expressions. Experiment with different quanitifiers to enhance your text processing tasks. 

## About the Author 

This tutorial was written by Taylor Campanelli, student at UT Austins coding bootcamp. Check out [My GitHub Profile](https://github.com/Camparooni) to see more of my work

