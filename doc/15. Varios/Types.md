# Tipos de Datos  

### **Quad**  
`x: number`  
`y: number`
`w: number`  
`h: number`  
`scale(q: Quad) => Quad`  
`pos() => Vec2`  
`clone() => Quad`  
`eq(q: Quad) => boolean`  

### **Vec2**  
`x: number`  
`y: number`  
`LEFT: Vec2`  
`RIGHT: Vec2`  
`UP: Vec2`  
`DOWN: Vec2`  
`fromAngle(deg: number) => Vec2`  
`clone() => Vec2`  
`add(p: Vec2) => Vec2`  
`add(x: number, y: number) => Vec2`  
`sub(p: Vec2) => Vec2`  
`sub(x: number, y: number) => Vec2`  
`scale(s: number) => Vec2`  
`scale(sx: number, sy: number) => Vec2`  
`dot(p: Vec2) => number`  
`cross(p2: Vec2) => number`  
`dist(p: Vec2) => number`  
`sdist(p: Vec2) => number`  
`len() => number`  
`slen() => number`  
`unit() => Vec2`  
`normal() => Vec2`  
`reflect(normal: Vec2) => Vec2`  
`project(on: Vec2) => Vec2`  
`reject(on: Vec2) => Vec2`  
`angle(p: Vec2) => number`  
`angleBetween(args: ...) => number`  
`lerp(p: Vec2, t: number) => Vec2`  
`slerp(p: Vec2, t: number) => Vec2`  
`isZero() => boolean`  
`toFixed(n: number) => Vec2`  
`transform(n: Mat4) => Vec2`  
`bbox() => Rect`  
`eq(p: Vec2) => boolean`  

---
[Índice](https://github.com/mishicoder/KaboomDoc-ES-/blob/main/doc/1.%20Introduccion/0.%20Indice.md)