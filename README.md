# platypus
Interact with obsidian vaults as structured data outside of obsidian

status: not useful

## motivation
Obsidian can feel a bit restricitve, in that you have all these amazing tools to create and manipulate data, but only inside of obsidian. I would really like more tools that work in obsidian vaults but do not need to be a plugin. For example, I use the [pomodoro plugin](<https://github.com/eatgrass/obsidian-pomodoro-timer>) for obsidian, and I love it, it lets me log work, and I then use [dataview](<https://github.com/blacksmithgu/obsidian-dataview>) to query that data. My issue is that all of this happens in obsidian, I think it would be awesome to be able to have a pomodoro timer or similar that just logs in your daily note with no further thought, and I would like to be able to query that data very easily.

My other issue is with portability, yes its all markdown, but so so much of what makes obsdian fun and useful relies on the tooling, but most of it is locked inside of obsidian.

## goals
- rust library for interacting with obsidian vaults
- some form of cli that is both good for shell scripting, and good for quickly querying your vault
- (maybe (very likely no!)) python library
- useable with dataview `[key:: value]` blocks
- be able to query vault metadata, such as plugins etc
- obsidian core template useage
- templatr plugin (maybe, i do not know how doable this actually is)
