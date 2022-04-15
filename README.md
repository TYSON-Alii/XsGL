### XsGL [Modern, Type Safe, Functional Opengl]

```cpp
void draw_square() {
  gl.Disable(gl.Texture2D);
  gl.Ident();
  gl.Translate(0,0);
  gl.Rotate(45.f);
  gl.Scale(1.f);
  gl.Color(1,1,1,1);
  gl.Begin(gl.Quad);
  gl.Vertex(1, 1);
  gl.Vertex(1, 0);
  gl.Vertex(0, 0);
  gl.Vertex(0, 1);
  gl.End();
}
```
