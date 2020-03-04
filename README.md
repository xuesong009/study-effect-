## 03 小米商城 translate3d(x,y,z)
###用户(评价)部分
设计思路：

 (1) 默认情况下，用户评价部分 不显示：
   - 最外层容器.outer的高度不包含用户评价部分的高度；
   - 为.outer容器设置overflow：hidden;

 (2) 当鼠标悬停时，从底部滑出：
   - 距离容器.outer底部bottom：由-height-->height;