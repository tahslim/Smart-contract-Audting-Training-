# Secureum Solidity 201 (Five) Topic Review

## 1 - Modifier Overriding

From experience we notice some function modifiers can override each other. This works in the same way as function overriding (except that there is no overloading for modifiers). The main point to stick to is that the virtual keyword must be used on the overridden modifier while the override keyword must be used in the overriding modifier.

## 2 - Name Collision Error

Many times we inadvertently use the same name  for different fucntions which returns an error. It is important to be mindful whenan error when any of the following pairs in a contract have the same name due to inheritance: 1) a function and a modifier 2) a function and an event 3) an event and a modifier.

## 3 - Reserved Keywords

More often that not we creatively use some of Solidity's keyword which returns an error and have to be avoided when writing smart contracts. Some of these keywords are reserved in Solidity. They might become part of the syntax in the future: after, alias, apply, auto, case, copyof, default, define, final, immutable, implements, in, inline, let, macro, match, mutable, null, of, partial, promise, reference, relocatable, sealed, sizeof, static, supports, switch, typedef, typeof, unchecked.

## 4 - OpenZeppelin Libraries

Every seasoned solidity developer knows that working smart is the rule of writing complex smart contracts, and as such, to avoid several complications, its more required that advised that OpenZeppelin’s smart contract libraries are used. These include contracts for popular token standards, access control, security, safe math, proxies and other utilities.

## 5 - Overflow/Underflow Check

One of a nightmares often faced by smart contracts containing complex mathematical structures is having an overflow/underflow bug which can be exploited by an attacker. Until Solidity version 0.8.0 which introduced checked arithmetic by default, arithmetic was unchecked and therefore susceptible to overflows and underflows which could lead to critical vulnerabilities. The recommended best-practice for such contracts is to use OpenZeppelin’s SafeMath library for arithmetic.
