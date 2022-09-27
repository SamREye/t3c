# Tezos Contract Convention Catalogue

An organization for developing conventions for smart contracts

> TLDR: T3C is an free, open, searchable, deployable collection of contract templates as well as interface definitons, with interface verifiers.

## Background

In the Tezos Developper community, there exists Standards; e.g. FA1.2 and FA2, which are the most notable. Said standards are defined in the TZIP process.

T3C contains Conventions--submitted by the community--, which are not (or not yet) recognized broadly as to be considered Standards. Although there is no reason why a Convention could/would/should not become a recognized Standard... however, a convention at its simplest does not require anyone else's permission or recognition.

## Definitions

**Standard**: A template, or set thereof, that is a recognized and approved means of solving a problem; e.g. FA1.2 is a recognized means of tracking a ledger for a fungible token.

**Convention**: A defined means of operating, which is adopted by some, in order to solve a problem--may be concrete or abstract.

**Interface**: A minimum requirement of expectation from one party (i.e. a contract) in order to interoperate with another; usu. a set of well-defined entrypoints.

**Template**: A model contract which can serve as a pattern for other contracts.

## Need for T3C

1. To facilitate code reuse;
1. to enable interoperability between various contracts.

## Approach

1. A collection of contract models, which can be used as both templates and as copiable patterns;
1. A collection of interface definitions, which allow existing contract patterns to interoperate with other contracts.

## Benefits

1. Templates are--at least--guaranteed to be deployable, since the original must be an already deployed contract. (Often templates are posted on websites in text format, which may contain typos, syntax errors, or simply be out-of-date.)
1. Templates can be made deployable by an on-chain call from a pre-configured factory.
1. Interfaces can be verified on-chain; so that a service contract can validate a client contract's interface to ensure the interoperability between the two.
1. Allows the author(s) to retain some evidence of authorship, as well as the ability to license templates. A license holder may change license fees for deployment of a licensed template.

## Components

 * Template Catalogue
   * search for template
   * register template
   * deploy new instance from template
 * Interface Catalogue
   * search for interface
   * register interface
   * verify a contract whether it meets the interface criteria

## Governance

The T3C is a body that applies its own principles and is built on its own templates and interfaces.

Its governance is that of a Constitutional Not-For-Profit Body.
