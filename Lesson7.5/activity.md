### @hideIteration true 

<!-- block combinations that will show up by default in their workspace -->
```template
player.onChat("run", function () {
})
```

<!-- blocks you want available to players, based on js code -->
```blocks
player.onChat("run", function () {})

agent.move(FORWARD, 1)
agent.turn(LEFT_TURN)
agent.detect()

if (true) {}
if (agent.inspect(AgentInspection.Block, FORWARD) == GRASS && false) {} else {}

while (!(agent.detect(AgentDetection.Block, FORWARD))) {}

```

# Tinker Coder
## Lesson 7.5
### Welcome!

In this lesson, you will apply what you have learned to solve a series of mazes.

For more instructions, go to Lesson 5 in your book. Be sure to read all the instructions. There are also some hints to help you. 

As you code, make sure you DO NOT delete any of the code that you have successfully used. At the end of the lesson, you can show off what you have built, and your code to your parent/guardian.

<sub>*You must only use the blocks given here. If you are found to be using other blocks, trying to get around the controls of the map, or building yourself, the map will be reset and you will have to start over. No extra time will be given in these cases.*</sub>
