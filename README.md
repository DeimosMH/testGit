##	Test Git repository

This repository is used for testing new features and add-ons of in GitHub connection with:

- [Git CMD/Bash](https://git-scm.com)
- [GitKraken](https://www.gitkraken.com)
- [Visual Studio Code](https://code.visualstudio.com)
- [Visual Studio 2019](https://visualstudio.microsoft.com/pl/downloads/)

Markdown editor:

- [Typora](https://typora.io) 



### Test site with animated bg 

$$
init \rightarrow commits: main \rightarrow branch:[ crazyColors \leftarrow main] \rightarrow merged\; output \\ 
commits: crazyColors \rightarrow stagging\; area \rightarrow merge:main
$$

```mermaid
graph LR
A(init)-->B(commits: main)
B-->|main| F
B-->C(branch: crazyColors)
C-->|crazyColors| D(commits)
D-->E(stagging area)
E-->F(merge: main)
F -->|merged| O(output)
```

Files: 

- index.html
- styles.css
- app.js

