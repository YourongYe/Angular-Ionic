# class vs id
class example:
```css
.question-card{
  // position: absolute;
  height: 200px;
  width: 300px;
  // top: 5%;
  // padding-bottom: 5px;
  visibility: visible;
}
```
id example:
```css
#balloon-effect{ 
  position: absolute;
  width: 100%;
  bottom: -100%;
  transition: ease-in-out;
  animation-name: balloon-animation;
  animation-duration: 5s;
  animation-play-state: paused;
  z-index: 2;
}
```
# animation
```css
#balloon-effect{ 
  position: absolute;
  width: 100%;
  bottom: -100%;
  transition: ease-in-out;
  animation-name: balloon-animation; // define animation name
  animation-duration: 5s;
  animation-play-state: paused; // define animation status, can be changed later in js
  z-index: 2;
}

@keyframes balloon-animation {
  0%   {bottom:-100%;}
  100% {bottom:100%;}
}
```

# z-index (define layers)
z-index 越大，越在上层  
For example:   
z-index: -1   (最下层)
z-index: 0     
z-index: 1    （最上层）


# Page overflow (内容是否溢出当前页面)
```css
.card{
  background: rgba(255, 255, 255, 0.62);
  height: 40%;
  overflow: hidden; // 如果当前字段或图片大小超过当前页面，或者所在section/division所定义的大小，则超过部分会被隐藏，不能被查看
}
```

```css
.card{
  overflow: visible; //可以通过滑动被看见，会延长当前页面，这也是默认的设置
}
```
