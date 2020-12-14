# 移动端中的hover问题

移动端中，如果给元素添加hover效果，手指离开后，依然保持hover状态。

使用媒体查询：

```
@media (any-hover: hover) {
  a:hover {
    background: yellow;
  }
```

PC支持hover事件，移动端不支持？
