# Minimal POC for describing buildings using custom HTML entities (Tags)
Developed based on conversations with [JosepMariaPujol](https://github.com/JosepMariaPujol/HTML-Build) 

The original idea was to use custom HTML entities to represent building entities, however this proved idfficult with vanilla HTML and ended up using DIVs and giving them custom CSS classes to represent the building entities.

So now te repo uses the [YAX custom entities tutorial](https://tutorials.yax.com/learn/your-first-custom-html-tag/index.html) to provide a building as HTML example project, that others can build in.

Design principles / assumptions are.

1. Follow IFC as much as possible
2. Use HTML5 principles to solve all problems
3. Make it super easy to hack
4. Have fun

4/10/22: Canøt embed the children - Lit overwrites it... looks like need to do something called slotting - but this seems to increase the complexity and reduce the fun...