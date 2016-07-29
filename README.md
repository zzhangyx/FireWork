# FireWork
直播间送礼物之烟花效果

#How To Use(Too Simple)
//1.新建一个烟花效果
FireWorkView fireWorkView = new FireWorkView(MainActivity.this, R.drawable.heart);
//2.在布局上增加烟花效果
LinearLayout.LayoutParams layoutParams = new LinearLayout.LayoutParams(-1, -1);
linearlayout.addView(fireWorkView, layoutParams);
//3.播放动画
fireWorkView.playAnim();
        
#效果图
![image](https://github.com/jingtianxiaozhi/FireWork/blob/master/gif/rose.gif?raw=true)

![image](https://github.com/jingtianxiaozhi/FireWork/blob/master/gif/heart.gif?raw=true)


