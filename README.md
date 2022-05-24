# Chess
Implementation of a chess game in Kind

# Usage
1. Install kind using ``npm``:

``
 npm i -g kind-lang
``

2. This repository should be in base/App 

4. Install js-beatutify using ``npm``:

``
   npm i -g js-beautify
``

4.Build the app:

``
node web/build Chess
``

5.Run a local server:

``
node web/server.js 8080
``

6.Open http://localhost:8080 in you favorite browser

7.Have fun!

# How it works?

In Chess game every piece is a number of bits :

![white](https://user-images.githubusercontent.com/95002561/170084977-c2159ccd-d4f8-4a6b-b201-d02ed2ae7aa3.png)

![black](https://user-images.githubusercontent.com/95002561/170085241-909fd0f9-bdb3-4d9a-b256-64097ebbdfc7.png)

In the Board:

![board](https://user-images.githubusercontent.com/95002561/170085600-49471e62-b52b-4114-a9b0-fb9d1097cc05.png)

and we use a sistem to identify the tiles: 

$$\forall n \in 0 \leqslant n< 64 $$

$$x \equiv n \(\bmod\ n) $$

$$y =  \left \lfloor \frac{n}{8} \right \rfloor$$

![chessmod](https://user-images.githubusercontent.com/95002561/170087727-d40adca1-ce83-40a1-ba78-269715787766.png)

