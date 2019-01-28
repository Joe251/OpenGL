# OpenGL
## Progress of learning OpenGL

### Vertex Buffers
- The GPU should be told the layout of the buffer, like how many values are assigned to X, Y e.t.c. <br/>
- **!Important:**
    - Vertex is way more than position, it can contains more data.<br/>
    - glVertexAttribPointer: stride means how many bytes should be jumped from one point to the next point<br/>
      - e.g, Point:(attr1: 10 bytes, attr2: 12 bytes, attr3: 10 bytes), 32 bytes should be jumped shifting from point1 to point2.<br/>
### Shader
- What is shader: A program run in the GPU, GPU play a major role in performing the graphical tasks<br/>
- **Shader type:** Vertex Shader & Frament Shader
