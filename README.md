# particles

Implements particle systems using openGL

TODO: Add a representative image for your project here

![jew](/images/jewish.gif)

## How to build

*Windows*

Open git bash to the directory containing this repository.

```
particles $ mkdir build
particles $ cd build
particles/build $ cmake -G "Visual Studio 16 2019" ..
particles/build $ start CS312-Particles.sln
```

Your solution file should contain two projects: `pixmap_art` and `pixmap_test`.
To run from the git bash command shell, 

```
particles/build $ ../bin/Debug/billboard
particles/build $ ../bin/Debug/confetti
particles/build $ ../bin/Debug/demo
```

*macOS*

Open terminal to the directory containing this repository.

```
particles $ mkdir build
particles $ cd build
particles/build $ cmake ..
particles/build $ make
```

To run each program from build, you would type

```
particles/build $ ../bin/billboard
particles/build $ ../bin/confetti
particles/build $ ../bin/demo
```

## Results

I added a feature which spawns particles on the cursor location. These particles shrink over time and are eventually deleted.

Particles shrinking:

![size](/images/particles.gif)

Following the cursor:

![cursor](/images/cursor.gif)

Colors change over time:

![time](/images/changingcolor.gif)

Alternating between two colors:

![bi](/images/bicolor.gif)
