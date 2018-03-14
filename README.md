# Nihilistic Theme!

**Disclaimer:** There is nothing "nihilistic" about this theme, I just liked the sound of it

The principles, in order of priority, for this theme are
- **Consistency:** Colors are applied based on useful rules, making sure that the same piece of code won't have different colors when unrelated factors change. This also includes adding  exceptions in the CSS to make the colors actually more consistent.
- **Focus:** Make things that matter grab attention, and make things that contain no data dimmed
- **Few colors:** Currently using 5 (one of those being TODO and NOTE only) + 2 dimmed versions

### Rules

- Operators, most keywords, punctuation  
  **All Dimmed**
- Local variables  
  Meaning something that is not exported in any way out of the current file/context.  
  **Light**
- Propertyies/names  
  This is all the stuff that you can not decide the name for: in most cases properties of objects come from different libraries - have a certain static name/key that has to be used. This also includes mathematical and baked in "method like" operators like "===" and "+".
  **Darker**
- Control flow/important keywords  
  Some keywords are too important to dim  
  **White**
- Values: strings, numbers, etc  
  hardcoded stuff  
  **Blue**
