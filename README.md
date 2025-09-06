<h1>Racing Game</h1>
<p>Passing the tracks with barriers.</p>
<ul>
  <li>Windows</li>
  <li>Landscape orientation</li>
</ul>

<h2>Concept:</h2>
<p>The main character - racnig car.</p>

<p>The project is a racing track with barriers which the player must avoid while driving to the finish line.</p>

<p>The UI is relatively minimalistic: "start", choice of "difficulty level" and "exit".</p>

<h2>Life cycle:</h2>
<ol>
  <li>Launch/start the game by pressing the «START» button in the start menu.</li>
  <li>Screen with the firts level.</li>
  <li>Passing the racing track from the START point to the FINISH point, avoiding barriers.
</li>
  <li>The player wins when he successfully reaches the «FINISH» line. The «You won» screen is activated, showing the points earned, and also offering to play the game again by pressing the «RESTART» button. The transition to point 1 occurs.
</li>
</ol>

<h2>Mechanics and features:</h2>
<h3><u>Core mechanics:</u></h3>
<ul>
  <li>The player is controlled by pressing the keys W, A, S, D.</li>
  <li>The player «scares» by pressing the Q key.
</li>
  <li>The player moves through the labyrinth without passing through its walls and enemy creatures.
</li>
  <li>A player loses (lives) when touching an enemy creature.
</li>
  <li>When a player approaches, the static enemy turns towards the player and attempts to attack him.
</li>
  <li>A static enemy dies when hit by a «scream».
</li>
  <li>A dynamic enemy patrols part of the labyrinth corridors along a given route.
</li>
  <li>A dynamic enemy dies when hit by a «scream».
</li>
  <li>Pressing the Q key causes the player to emit a «scream» that, when it hits an enemy creature, takes away its life.
</li>
    </ul>

<h3><u>Additional-mechanics:</u></h3>
<ul>
  <li>The player collects bonuses in the form of signs and receives points for this.
</li>
  <li>Upon reaching the finish line, the player is transferred to the next level.

  <li><ul>
    <li>Level 1 – all enemies are static and to pass the level you need to «scare» them.
</li>
    <li>Level 2 (stealth) – all enemies are dynamic and move around the labyrinth, but you cannot attack them, you can only avoid them in other parts of the labyrinth.
</li>
    <li>Level 3 – static and dynamic enemies that can be «scared».
</li>
 </ul>   

  <li>The dynamic enemy does not move along a set path, but between certain points in a random order, independently choosing the shortest path.
</li>
  <li>When the player is at close range, the dynamic enemy begins to pursue him, deviating from its route.
</li>
  <li>When the player is very close to a dynamic enemy, the enemy will begin to attack him.
</li>
  <li>Score points for «scaring» an enemy creature.
</li>
    </ul>

<h3><u>Juice mechanics:</u></h3>
<ul>
  <li>The player cannot complete the level until he collects all the bonuses and/or «scares» all the enemy creatures.
</li>
  <li>Moving/pushing objects in a maze is similar to the game «Sokoban».
</li>
  <li>Adding objects that can be moved around the maze.
</li>
  <li>Adding a new level that features object movement mechanics.
</li>
</ul>

<h2>Build:</h2>
<p>The project build can be downloaded from the following link:</p>
<href>https://drive.google.com/drive/folders/1z7Iwz9mDxn-Se7nz2GD5uKlqZiCrbak8?usp=drive_link</href>
<h2>Launch instructions:</h2>
<p>1. Download the project build from the link.</p>
<p>2. Unzip the downloaded files if they were downloaded as an archive.</p>
<p>3. Launch My project.exe.</p>
