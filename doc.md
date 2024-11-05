設計
基本的なスプライトの考え方
```
class Sprite {
  pos: {x, y}
  isDead // trueの場合、次回からupdate()やdraw()が呼ばれなくなる
  init() {}
  update() {}
  draw() {}
  onHit(other, otherGroupName) {}
}
```