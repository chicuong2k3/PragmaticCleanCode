# Pragmatic Clean Code

## Boy Scout Rule: 

"Leave the code cleaner than you found it".

## Broken Window Theory

- Insignificant issues or defects can lead to large problems.
-> Fix any issues as soon as they are discovered.

## Principles

- [YAGNI](https://martinfowler.com/bliki/Yagni.html)
- KISS -> easy to understand, read, maintain and give a better UX
- The principle of Lease Surprise
- DRY -> duplicate the code doesn't mean duplicate the text, it refers to behaviours that change together.
- Write Idiomatic Code -> obey to Conventions and Stardards 

## What's our desire

- Loose Coupling
- High Cohesion
- Readability or Performance:
  1. Write Clean Code
  2. Cover it with tests
  3. Improve performance

## Rules

### Naming

```c#
public class Product
{
    public DateTime ProductCreatedOn { get; init; } 
}
```

The 'Product' in 'ProductCreatedOn' is redundant.









