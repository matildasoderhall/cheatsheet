# Code smells checklist

| Done?    | Code smell | Meaning | 
| -------- | ---------- | ------- | 
| - [ ] | Mysterious Naming | Unintelligible names for functions, variables, modules, or classes	 |
| - [ ]| Duplicated Code | The same code appears in multiple places | 
| - [ ] | Excessively Complex Code | Code is overly complicated | 
| - [ ] | Shotgun Surgery | Small changes required in many places | 
| - [ ] | Side Effects | Changing one part causes unexpected issues elsewhere | 
| - [ ] | Comments | Comments describe what happens instead of why it happens | 
| - [ ] | Long Methods | Functions that do too many things simultaneously | 
| - [ ] | Too Many Function Parameters | Long list of function parameters; consider converting them into an object? | 
| - [ ] | Combinatorial Explosion | Similar code in multiple places; needs abstraction | 
| - [ ] | Large Constructs Overall | Large functions, large classes; refactor into smaller, isolated components | 
| - [ ] | Types in Variable Names | const nameStr = 'Jenni'; → const name = 'Jenni'; | 
| - [ ] | Poor Naming | Same issue as mysterious naming	 | 
| - [ ] | Inconsistent Naming | If you write open(), you probably shouldn’t write Close() | 
| - [ ] | Dead Code | Refactor ruthlessly! | 
| - [ ] | Code for the Future | Avoid "just in case" code—it’s rarely useful	| 
| - [ ] | Different Solutions to Nearly Same Problem | Similar to duplicated code | 
| - [ ] | Cherry-Picking | Only pass along what’s truly necessary | 

