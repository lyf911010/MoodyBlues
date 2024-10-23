# ios swiperjs中 元素position:absolute失效问题
原因：transform属性在ios中对定位属性影响  
解决：定位元素加上transform: translate3d(0,0,0)