- Android-PullToRefresh的用法

attrs 属性

 ptrRefreshableViewBackground //刷新背景图
 ptrHeaderBackground  //上拉下拉加载图
 ptrHeaderTextColor //上拉下拉加载文字颜色
 ptrHeaderSubTextColor ////上拉下拉子头加载文字颜色
 //刷新模式
 ptrMode //disabled pullFromStart pullFromEnd both manualOnly pullDownFromTop pullUpFromBottom
 ptrShowIndicator //是否显示Indicator
 ptrDrawable //Indicator图片
 ptrDrawableStart //Indicator图片头部
 ptrDrawableEnd //Indicator图片尾部
 ptrOverScroll //滑动
 ptrHeaderTextAppearance //加载图像基本样式
 ptrSubHeaderTextAppearance //加载图像基本样式
 ptrAnimationStyle //rotate flip
 ptrScrollingWhileRefreshingEnabled  //滑动时是否可以滚动
 ptrListViewExtrasEnabled 
 ptrRotateDrawableWhilePulling 
 //已废弃 不要使用了
 ptrAdapterViewBackground 
 ptrDrawableTop 
 ptrDrawableBottom 

//最基本的列表
<com.handmark.pulltorefresh.library.PullToRefreshListView
        android:id="@+id/pull_refresh_list"
        android:layout_width="fill_parent"
        android:layout_height="fill_parent"
        android:cacheColorHint="#00000000"
        android:divider="#19000000"
        android:dividerHeight="4dp"
        android:fadingEdge="none"
        android:fastScrollEnabled="false"
        android:footerDividersEnabled="false"
        android:headerDividersEnabled="false"
        android:smoothScrollbar="true" />