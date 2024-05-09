# fixed gs++
## GS++ would always crash on load for me, so I decided to fix it and upload the jar here.

![Static Badge](https://img.shields.io/badge/Made%20By%20-%20Wizard_11%20-%20purple)

This was super easy to fix, I used a program called [Recaf](https://github.com/Col-E/Recaf/releases) to decompile the downloaded jar, and edit it to prevent the disabling of jndi.

This fixed the issue:

```
public static void disableJndiManager() {
   // but i dont wanna...
}
```

Enjoy!

> Credits to TechAle for making GS++


Check out some of my other projects, like my [1.16-1.20 client archive](https://github.com/AGENTISNUM1/1.16-1.20-client-archive)
