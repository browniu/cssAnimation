# CssAnimation
> 纯CSS3实现细腻的交互动效果

## 百分比进度环
```css
/*1*/
@keyframes rotate1 {
    0% {
        transform: rotate(0deg);
    }
    100% {
        transform: rotate(360deg);
    }
}
```

## 混沌环
```css
@keyframes rotate2 {
    0% {
        transform: rotate(0deg) translateY(-2px);
    }
    100% {
        transform: rotate(360deg) translateY(-2px);
    }
}
```

## 混沌环
```css
@keyframes rotate2 {
    0% {
        transform: rotate(0deg) translateY(-2px);
    }
    100% {
        transform: rotate(360deg) translateY(-2px);
    }
}
```

## 水波纹
```css
@keyframes move1 {
    0% {
        left: 0;
    }
    100% {
        left: -80px;
    }
}
@keyframes move2 {
    0% {
        left: -20px;
    }
    100% {
        left: -100px;
    }
}
```

## 抖动
```css
@keyframes shake {
    0% {
        transform: rotate(0deg);
    }
    4% {
        transform: rotate(-5deg);
    }
    8% {
        transform: rotate(5deg);
    }
    12% {
        transform: rotate(-5deg);
    }
    16% {
        transform: rotate(5deg);
    }
    20% {
        transform: rotate(-5deg);
    }
    24% {
        transform: rotate(5deg);
    }
    28% {
        transform: rotate(0deg);
    }
}
```

## 跳跃
```css
@keyframes jump {
    0% {
        transform: translateY(0px);
    }
    50% {
        transform: translateY(-10px);
    }
    100% {
        transform: translateY(0px);
    }
}
```

