[likerpx](https://github.com/devchn/likerpx)

# 在普通 html 项目上使用 likerpx

#### 下载
https://github.com/devchn/likerpx

#### 引入

```
<script src="likerpx.js"></script>
```

#### 使用

因为没有 postcss，所以只能使用 rem 来代替 rpx。

750rpx=.750rem

```css
<style>
.box {
  width: .100rem;
  height: .100rem;
  background-color: red;
}
</style>
```