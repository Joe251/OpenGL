# OpenGL
## Progress of learning OpenGL
### Some helpful websites
***http://docs.gl/***<br/>
***https://www.glfw.org/***<br/>
***http://glew.sourceforge.net/***<br/>
***http://antongerdelan.net/***<br/><br/>
### Vertex Buffers
- The GPU should be told the layout of the buffer, like how many values are assigned to X, Y e.t.c. <br/>
- **!Important:**
    - Vertex is way more than position, it can contains more data.<br/>
    - glVertexAttribPointer: stride means how many bytes should be jumped from one point to the next point<br/>
      - e.g, Point:(attr1: 10 bytes, attr2: 12 bytes, attr3: 10 bytes), 32 bytes should be jumped shifting from point1 to point2.<br/>
### Shader
- What is shader: A program run in the GPU, GPU play a major role in performing the graphical tasks<br/>
- **Shader type:** Vertex Shader & Frament Shader
### Index Buffer
Using Index Buffer to draw object can save the cost of storing duplicated data, sometimes we need to draw the same point multiple times, instead of storing the duplicated vertices again, we can specific a unique buffer of the positions of the vertices, when drawing an object, all we have to need is to tell the computer the indices of the vertices.<br/>
