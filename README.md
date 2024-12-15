Ninja Physics is a web game, that inspired by Gorillas, a game that was published by Microsoft in 1990. It is a turn-based artillery game
where the gorillas throw exploding bananas each other in city skyline (a reference to King Kong). Personally, my aim in this project is to
make physics more enjoyable and engaging for younger audiences. As someone who loves physics, I am sorrowful to see that homework and grades 
because of the difficulty of their curriculum.
In order to make physics more fun and engaging, I decided to use "gamification". I chose a ninja theme to make the game even more interesting
and cool, so to speak. I coded the game with JavaScript, HTML and CSS languages. When you enter the website, you are welcomed by a homepage, 
that is linked to a guide, and the game itself. The guide page starts by defining what the projectile motion is and introduces the player to the concept. 
It covers fundamental terms like velocity, angle and gravity. Here, the player can learn about how these parameter affect the trajectory of the projectile, 
before stepping into the game. The controls of the game are also explained in this game. Ninja Physics uses sliders instead of directly prompting the player 
to input a value. This allows the students to experiment around with the values without having to be too concise with their argument. Hence, they can experiment 
around with the values and observe how the motion changes after changing the parameters. Furthermore, there is a part at the end of the page that provides with the 
kinematics formulas for projectile motion, in case students want to take it one step further and calculate exact values for their angles and velocity. 
Though not necessary, doing this will definitely increase the precision of the student, making them a real ninja!
The game itself takes place in a city in the sunrise, where two ninjas have a fierce duel. In the background, we see faint silhouettes of buildings and in the front, 
we see the main buildings. On the second building from left stands one ninja and on the second building from right stands the other. They take turns to throw shurikens
at each other while avoiding hitting the buildings.There are various mechanics implemented in the game. First of all, I used javascript to randomly generate height of both the
main and background buildings. Every time a new round begins, the buildings are generated randomly to create an element of surprise. This way, the game does not become repetitive
and boring. The positions of the buildings are very important, as the projectiles can not pass through them.
This forces the users to carefully adjust their trajectory, introducing an element of "skill" into game. Though the background buildings are just for aesthetics, the main buildings
are an interactive part of the game. When the shurikens (throwable weapons of ninjas) hit the main buildings, they leave holes in them. With enough determination, you can even rip 
through buildings! Moreover, Ninja Physics provides a follow-through path, which hints at how the shuriken will take off depending on its velocity and angle. This works by drawing a dashed-line,
the magnitude and direction of which depends on velocity and angle.
I used javascript to define a game state, that holds important information such as the phase (aiming | in flight | celebration), positions of ninjas and the shuriken, shuriken's rotation and more.
This definiton allows me to access this data in other pieces of code. I used javascript to randomly assign height to buildings and also make sure that the game area is scaled appropiately to fit the
user's screen. I developed a various functions, that process user input and throw the projectile accordingly. I animated the game by using appropiate formulas, figuring out where the shuriken will be
in the next instant and updating its position accordingly by utilizing "timestamp". I further improved the motion by adding a multiplier logic so that no matter how long it takes to render a frame, 
it will be multiplied by a constant that correlates with the elapsed time to ensure that the animation is smooth. I worked on a hit detection system, that detects if the projectile got out of the 
screen borders, hit a building, or hit the enemy ninja.
I used HTML canvas to draw almost everything on the screen, as I found it the most straightforward and functional method for developing a game like this. I made it into a browser based game, 
so that students could find different platforms to play this game on. It can even be played on the smartboards at school, and might even be used to teach projectile motion in a real physics lesson!