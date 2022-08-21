# datagrip-pretty-unicode-extractor
A unicode table data extractor for Jetbrains Datagrip

Just like the `Pretty-Groovy.txt.groovy` file that is included with Datagrip, but modified to use Unicode table characters, e.g.

```
from this:       to this:
+---+---+        ┌───────┐    
|a  |b  |        │a  │b  │    
+---+---+        ├───┼───┤    
|foo|123|        │foo│123│    
|bar|456|        │bar│456│    
+---+---+        └───┴───┘    
```

See the [Datagrip Documentation](https://www.jetbrains.com/help/datagrip/data-extractors.html#creating-any-text-extractor-with) for instructions on how to add this to your Datagrip.
