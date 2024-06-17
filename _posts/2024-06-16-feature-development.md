---
title: "Bringing functional requirements to life: a puzzle lover's dream"
date: 2024-06-15
categories:
  - product
  - blog
tags:
  - technical
  - features
---

I dove into this project with minimal technical knowledge. But as part of my learning journey, I was committed to be the developer for my app, at least in its early stages. Learning to code in the timeframe I wanted to launch was not possible, so I took the next best option: using a no code app builder. 

Even without learning the syntax of any particular coding language, there was still a steep learning curve. To my surprise, most of this development work was exactly what I loved to do: solving puzzles! In building my app, I’ve practiced countless times the cycle: understanding a functional requirement, breaking it down into smaller parts, implementing and testing it, and readjusting the logic until the requirement was met. 

Figuring out how to design and implement each feature was a fun challenge. Even a seemingly simple interaction from a user’s perspective might be broken down into dozens of requirements. And once you have the broken-down requirements, there might still be multiple workflows that bring the requirements to life. 

Due to this complexity, I’ll be honest and say I rarely get the technical implementation right the first time. I’m almost tired of hearing myself ask “why is it doing that?!” during testing. But this is also where the most exciting problem solving lives. The feeling of getting it to finally work the way you want is incredible!

To illustrate a bit of the thinking that goes into each part of the app, here’s a non-exhaustive list of considerations for a simple “virtual game room” feature. Keep in mind this was only a small (and non-unique, many other games have this as well) part of the entire app, so you can imagine how much longer this list truly is!

<h3>Select a Game</h3>
| Functional Requirements | Implementation |
|--------|---------|
|Allow host to select a game|
<ul>
	<li>Create a “Select Game” button under the game title.</li>
	<li>Only allow the player to select the game if the player owns the game. </li>
	<li>If they don’t own any games, redirect them to the games shop.</li>
</ul>|


| Functional Requirements | Implementation |
|--------|---------|
|Allow host to select a game|<ul><li>item1</li><li>item2</li></ul>|

<h3>Select a Game</h3>
| Functional Requirements | Implementation |
|--------|---------|
|Allow host to select a game|Create a “Select Game” button under the game title. Only allow the player to select the game if the player owns the game. If they don’t own any games, redirect them to the games shop.|

<table>
<colgroup>
<col width="30%" />
<col width="70%" />
</colgroup>
<thead>
<tr class="header">
<th>Functional Requirement</th>
<th>Implementation Component</th>
</tr>
</thead>
<tbody>
<tr>
<td markdown="span">**Allow host to select a game**</td>
<td markdown="span">
		- Create a “Select Game” button under the game title.<br>
		- Only allow the player to select the game if the player owns the game.<br>
		- If they don’t own any games, redirect them to the games shop.<br>
</td>
</tr>
<tr>
<td markdown="span">**Host must enter a name**</td>
<td markdown="span">
		- Select game button opens a popup that prompts a name input.<br>
		- Only allow “Create Room” button to be clickable if the name input is at least 1 character long.<br>
</td>
</tr>
</tbody>
</table>