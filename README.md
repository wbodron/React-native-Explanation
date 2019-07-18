# React-native-Explanation
Explanation of my workflow for development for React-native v0.60.x during the summer of 2019

# General
Development split between multipule machines can be annoying, my solution was to put everything into VC and keep things up to date with myself.
You could feasibly do your development on a network drive, but i'm afraid that would make the process slower than it is?

Doing all your development on a fast mac would be ideal. Macs can build code for both android and ios devices.

# Node/npm things
It's not explicitly stated in installation instructions, but its very important use Node10 instead of 12

```
brew install node@10
brew install npm
```
or
```
choco install node@10
choco install npm
```

npm explanation: 
the -g tag stores things in your global node-modules/
i is short for install
```
npm i
```
checks package.json and gets all the dependencies and devDependencies 

As of v0.60 certain android libraries require something called 'jetifier' to compile properly. this will probably not be an issue in the future, but as you'll likely stay on this version, 
```
npm install -g jetifier
```

# A case for Expo
It might have it's drawbacks, but for speed and reliability, I would highly recommend using expo. It takes away the frustration of getting build configurations working. It took me a whole day to work through the bugs of my android project on ios. With expo you can debug during development on both devices simultaneously. The newest version of expo supports sqlite, react Hooks, and typescript OUT OF THE BOX. 








