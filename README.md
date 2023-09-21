# Tutorial: Nx + Expo Todo App

## Part 1: Setup

Before we start, in VS code you'll need the [Nx console Extension](https://marketplace.visualstudio.com/items?itemName=nrwl.angular-console)

```bash
npx create-nx-workspace@latest --package-manager=yarn
```

options:
_Where would you like to create your workspace? ›_  
✔ Where would you like to create your workspace? · **todo-mono**
✔ Which stack do you want to use? · **react**
✔ What framework would you like to use? · **expo**
✔ Application name · **todo-mobile**
✔ Enable distributed caching to make your CI faster · **YES**

#### Add dev dependencies

Using the [Nx console](https://marketplace.visualstudio.com/items?itemName=nrwl.angular-console)

Go to **Common NX Commands** and select **Add Dev Dependency**
Then select Nestsjs and add it as a dev dependency, be sure to run the init prompt that comes up after the installation is done
