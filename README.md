# Project Description
This final project was to visualize the revolution and rotation of the solar system's nine planets, with some particles attached as a background. This project combines what I learned in weeks 6 and 7 and some expansions. The motivation for this project was that through my learning of three.js, I thought it was a very powerful platform that would allow us to quickly create a 3D world. Astronomy has always been a very interesting part of my life. So I just wanted to make a solar system, and I was the creator of this 3D world.
# Creating the world
In the first step, like with any other project, I created many variables, a scene, camera, lights, and much spherical geometry, placing the geometry in different positions. Many giant rings were also created to act as orbits for the planets to rotate around. This was similar to the other projects.
# Rotation and rotation
The first problem I had was that I needed to learn how to set up the planet's rotation. I searched for tutorials on W3School and the internet and followed along before I eventually learned how to set up the rotation. There are three ways to rotate the function.
1. rotate the camera 2. rotate the whole scene 3. rotate individual elements.
Because each planet in the solar system has a different rotation speed, so it is not feasible to set the whole rotation, so you have to set different rotation properties for each element.

So I first made up a group for each planet to achieve a different speed for each planet and rotate it simultaneously as it rotates. Next, a child element was set for each group, which served as the basis for the rotation. A different rotation rate was then set for each group, and finally, the rotation was achieved.
The rotation of a planet is relatively simple, and I learned in my lecture that the effect of a planet's rotation could be accomplished by having the object rotate according to the Y-axis.

# Creating particles
And to create particles for this project, I didn't use exactly what was taught in the week six lecture; I found it a little difficult for me, and I learned a new way of creating particle effects and wanted to give it a go. My initial thought was that if this didn't work, I would use the way I did in the lecture, but luckily it did.
This approach makes almost exclusive use of three.js. I use the geometry function. Random positions are set for each vertex, and textures are added to what ends up being an infinite (5000) number of stars.

# Future development
This project needs further optimization; firstly, I will add a richer background effect, like a sky box or some view in the Universe. Secondly, I will add a profile for each planet so that the profile of the corresponding planet will appear when the mouse is moved over the planet. Finally, I would add a piece of music to the whole scene.
