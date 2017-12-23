# j9-modularity
java 9 modularity basics

This repo deals with java 9 modularity basics

To compile use:
```javac -d mods/core.da src/core.da/module-info.java src/core.da/core/da/DataDemo.java```

If the compile phase is successful go to the next step, otherwise try to fix whatever issue had poped up.

To run use:
```java --module-path mods -m core.da/core.da.DataDemo```

If you see: 
Data demo...

Then you are good to go further, otherwise try to fix whatever issue you have.
