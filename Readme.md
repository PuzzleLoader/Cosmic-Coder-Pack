# Cosmic Coder Pack

This is a project that allows you to generate and run Cosmic Reach's source code from one jar from the [Cosmic Archive](https://github.com/CRModders/CosmicArchive)

Requirements:
- [Golang](https://go.dev)
- [Java (at least 17)](https://www.java.com/en/download/) *if the tool does not work your path env is messed up*
- [Git](https://git-scm.com/downloads)

**All the gradle functions you will need will be in the task folder of `cosmic_coder_pack`**

- To configure this project like choosing the version of things look in `gradle.properties`.
- To setup your work enviornment just run `setupWorkspace` in the tasks.
- If you want to make the decompilation errors disappear use the tasks `getBasePatches` and then `applyPatches`.
- If you want make your own patches look in the `patches` folder provided by `getBasePatches` or make your own `patches` folder. To apply those patches run the task `applyPatches`.
- To run your work start the task `runCosmicReach` and debug until it works.
- To compile this for other people run `createReleaseJar` and as a dev build (No Deps) run `createDevJar`
- To create a source jar launch `createSourcesJar`.
- If you want to make and share patches among devs just run the `generatePatches` task.

## ⚠️ Warning ⚠️
**Do not distribute code generated by this tool *unless you have explicit permission by [Final For Each](https://github.com/FinalForEach) to do so*.**

Not affiliated with FinalForEach or Cosmic Reach.