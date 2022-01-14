# Welcome to Folody!

Listening to music everytime with friends and relax Folody was created in `2021`, based on the idea of ​​music bots with some innovation and a little creativity.

### List commands

#### 1. `play` command


```mermaid
graph LR
A[Song name or link or image] -- String --> B(Search)
A -- Image --> C(Search)
C -- Have text --> E(Recognize text) --> F(String) --> B
B --> D{Play}
C --> D
```
