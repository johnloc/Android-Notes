# Android-Notes
Android开发核心知识点笔记-目录：  

## Java 知识点汇总

   * [JVM](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Java知识点汇总.md#jvm)
     * [JVM 工作流程](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Java知识点汇总.md#jvm-工作流程)
     * [运行时数据区（Runtime Data Area）](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Java知识点汇总.md#运行时数据区runtime-data-area)
     * [方法指令](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Java知识点汇总.md#方法指令)
     * [类加载器](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Java知识点汇总.md#类加载器)
     * [垃圾回收 gc](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Java知识点汇总.md#垃圾回收-gc)
       * [对象存活判断](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Java知识点汇总.md#对象存活判断)
       * [垃圾收集算法](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Java知识点汇总.md#垃圾收集算法)
       * [垃圾收集器](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Java知识点汇总.md#垃圾收集器)
       * [内存模型与回收策略](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Java知识点汇总.md#内存模型与回收策略)
   * [Object](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Java知识点汇总.md#object)
     * [equals 方法](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Java知识点汇总.md#equals-方法)
     * [hashCode 方法](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Java知识点汇总.md#hashcode-方法)
   * [static](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Java知识点汇总.md#static)
   * [final](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Java知识点汇总.md#final)
   * [String、StringBuffer、StringBuilder](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Java知识点汇总.md#stringstringbufferstringbuilder)
   * [异常处理](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Java知识点汇总.md#异常处理)
   * [内部类](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Java知识点汇总.md#内部类)
     * [匿名内部类](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Java知识点汇总.md#匿名内部类)
   * [多态](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Java知识点汇总.md#多态)
   * [抽象和接口](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Java知识点汇总.md#抽象和接口)
   * [集合框架](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Java知识点汇总.md#集合框架)
     * [HashMap](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Java知识点汇总.md#hashmap)
       * [结构图](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Java知识点汇总.md#结构图)
       * [HashMap 的工作原理](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Java知识点汇总.md#hashmap-的工作原理)
       * [HashMap 与 HashTable 对比](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Java知识点汇总.md#hashmap-与-hashtable-对比)
     * [ConcurrentHashMap](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Java知识点汇总.md#concurrenthashmap)
       * [Base 1.7](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Java知识点汇总.md#base-17)
       * [Base 1.8](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Java知识点汇总.md#base-18)
     * [ArrayList](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Java知识点汇总.md#arraylist)
     * [LinkedList](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Java知识点汇总.md#linkedlist)
     * [CopyOnWriteArrayList](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Java知识点汇总.md#copyonwritearraylist)
   * [反射](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Java知识点汇总.md#反射)
   * [单例](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Java知识点汇总.md#单例)
     * [饿汉式](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Java知识点汇总.md#饿汉式)
     * [双重检查模式](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Java知识点汇总.md#双重检查模式)
     * [静态内部类模式](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Java知识点汇总.md#静态内部类模式)
   * [线程](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Java知识点汇总.md#线程)
     * [状态](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Java知识点汇总.md#状态)
     * [状态控制](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Java知识点汇总.md#状态控制)
   * [volatile](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Java知识点汇总.md#volatile)
   * [synchronized](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Java知识点汇总.md#synchronized)
     * [根据获取的锁分类](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Java知识点汇总.md#根据获取的锁分类)
     * [原理](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Java知识点汇总.md#原理)
   * [Lock](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Java知识点汇总.md#lock)
     * [锁的分类](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Java知识点汇总.md#锁的分类)
       * [悲观锁、乐观锁](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Java知识点汇总.md#悲观锁乐观锁)
       * [自旋锁、适应性自旋锁](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Java知识点汇总.md#自旋锁适应性自旋锁)
       * [死锁](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Java知识点汇总.md#死锁)
   * [引用类型](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Java知识点汇总.md#引用类型)
   * [动态代理](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Java知识点汇总.md#动态代理)
   * [元注解](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Java知识点汇总.md#元注解)


## Android 知识点汇总

   * [Activity](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#activity)
     * [生命周期](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#生命周期)
     * [启动模式](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#启动模式)
     * [启动过程](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#启动过程)
   * [Fragment](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#fragment)
     * [特点](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#特点)
     * [生命周期](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#生命周期-1)
     * [与Activity通信](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#与activity通信)
   * [Service](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#service)
     * [启动过程](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#启动过程-1)
     * [绑定过程](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#绑定过程)
     * [生命周期](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#生命周期-2)
     * [启用前台服务](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#启用前台服务)
   * [BroadcastReceiver](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#broadcastreceiver)
     * [注册过程](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#注册过程)
   * [ContentProvider](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#contentprovider)
     * [基本使用](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#基本使用)
   * [数据存储](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#数据存储)
   * [View](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#view)
     * [MeasureSpec](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#measurespec)
     * [MotionEvent](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#motionevent)
     * [VelocityTracker](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#velocitytracker)
     * [GestureDetector](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#gesturedetector)
     * [Scroller](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#scroller)
     * [View 的滑动](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#view-的滑动)
     * [View 的事件分发](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#view-的事件分发)
     * [在 Activity 中获取某个 View 的宽高](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#在-activity-中获取某个-view-的宽高)
     * [Draw 的基本流程](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#draw-的基本流程)
     * [自定义 View](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#自定义-view)
   * [进程](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#进程)
     * [进程生命周期](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#进程生命周期)
     * [多进程](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#多进程)
     * [进程存活](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#进程存活)
       * [OOM_ADJ](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#oom_adj)
       * [进程被杀情况](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#进程被杀情况)
       * [进程保活方案](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#进程保活方案)
   * [Parcelable 接口](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#parcelable-接口)
     * [使用示例](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#使用示例)
     * [方法说明](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#方法说明)
     * [Parcelable 与 Serializable 对比](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#parcelable-与-serializable-对比)
   * [IPC](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#ipc)
     * [IPC方式](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#ipc方式)
     * [Binder](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#binder)
     * [AIDL 通信](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#aidl-通信)
     * [Messenger](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#messenger)
   * [Window / WindowManager](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#window--windowmanager)
     * [Window 概念与分类](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#window-概念与分类)
     * [Window 的内部机制](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#window-的内部机制)
     * [Window 的创建过程](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#window-的创建过程)
       * [Activity 的 Window 创建过程](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#activity-的-window-创建过程)
       * [Dialog 的 Window 创建过程](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#dialog-的-window-创建过程)
       * [Toast 的 Window 创建过程](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#toast-的-window-创建过程)
   * [Bitmap](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#bitmap)
     * [配置信息与压缩方式](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#配置信息与压缩方式)
     * [常用操作](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#常用操作)
       * [裁剪、缩放、旋转、移动](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#裁剪缩放旋转移动)
       * [Bitmap与Drawable转换](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#bitmap与drawable转换)
       * [保存与释放](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#保存与释放)
       * [图片压缩](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#图片压缩)
     * [BitmapFactory](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#bitmapfactory)
       * [Bitmap创建流程](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#bitmap创建流程)
       * [Option类](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#option类)
       * [基本使用](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#基本使用-1)
     * [内存回收](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#内存回收)
   * [屏幕适配](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#屏幕适配)
     * [单位](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#单位)
     * [头条适配方案](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#头条适配方案)
     * [刘海屏适配](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#刘海屏适配)
   * [Context](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#context)
   * [SharedPreferences](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#sharedpreferences)
     * [获取方式](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#获取方式)
       * [getPreferences](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#getpreferences)
       * [getDefaultSharedPreferences](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#getdefaultsharedpreferences)
       * [getSharedPreferences](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#getsharedpreferences)
     * [架构](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#架构)
     * [apply / commit](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#apply--commit)
     * [注意](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#注意)
   * [消息机制](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#消息机制)
     * [Handler 机制](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#handler-机制)
     * [工作原理](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#工作原理)
       * [ThreadLocal](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#threadlocal)
       * [MessageQueue](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#messagequeue)
       * [Looper](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#looper)
       * [Handler](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#handler)
   * [线程异步](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#线程异步)
     * [AsyncTask](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#asynctask)
       * [基本使用](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#基本使用-2)
       * [工作原理](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#工作原理-1)
     * [HandlerThread](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#handlerthread)
     * [IntentService](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#intentservice)
     * [线程池](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#线程池)
   * [RecyclerView 优化](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#recyclerview-优化)
   * [Webview](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#webview)
     * [基本使用](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#基本使用-3)
       * [WebView](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#webview-1)
       * [WebSettings](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#websettings)
       * [WebViewClient](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#webviewclient)
       * [WebChromeClient](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#webchromeclient)
     * [Webview 加载优化](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#webview-加载优化)
     * [内存泄漏](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android知识点汇总.md#内存泄漏)

## Android 扩展知识点汇总

   * [ART](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android扩展知识点.md#art)
     * [ART 功能](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android扩展知识点.md#art-功能)
       * [预先 (AOT) 编译](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android扩展知识点.md#预先-aot-编译)
       * [垃圾回收优化](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android扩展知识点.md#垃圾回收优化)
       * [开发和调试方面的优化](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android扩展知识点.md#开发和调试方面的优化)
     * [ART GC](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android扩展知识点.md#art-gc)
   * [Apk 包体优化](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android扩展知识点.md#apk-包体优化)
     * [Apk 组成结构](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android扩展知识点.md#apk-组成结构)
     * [整体优化](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android扩展知识点.md#整体优化)
     * [资源优化](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android扩展知识点.md#资源优化)
     * [代码优化](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android扩展知识点.md#代码优化)
     * [.arsc文件优化](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android扩展知识点.md#arsc文件优化)
     * [lib目录优化](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android扩展知识点.md#lib目录优化)
   * [Hook](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android扩展知识点.md#hook)
     * [基本流程](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android扩展知识点.md#基本流程)
     * [使用示例](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android扩展知识点.md#使用示例)
   * [Proguard](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android扩展知识点.md#proguard)
     * [公共模板](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android扩展知识点.md#公共模板)
     * [常用的自定义混淆规则](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android扩展知识点.md#常用的自定义混淆规则)
     * [aar中增加独立的混淆配置](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android扩展知识点.md#aar中增加独立的混淆配置)
     * [检查混淆和追踪异常](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android扩展知识点.md#检查混淆和追踪异常)
   * [架构](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android扩展知识点.md#架构)
     * [MVC](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android扩展知识点.md#mvc)
     * [MVP](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android扩展知识点.md#mvp)
     * [MVVM](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android扩展知识点.md#mvvm)
   * [Jetpack](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android扩展知识点.md#jetpack)
     * [架构](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android扩展知识点.md#架构-1)
     * [使用示例](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android扩展知识点.md#使用示例-1)
   * [NDK 开发](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android扩展知识点.md#ndk-开发)
     * [JNI 基础](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android扩展知识点.md#jni-基础)
       * [数据类型](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android扩展知识点.md#数据类型)
       * [String 字符串函数操作](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android扩展知识点.md#string-字符串函数操作)
       * [常用 JNI 访问 Java 对象方法](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android扩展知识点.md#常用-jni-访问-java-对象方法)
     * [NDK 开发](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android扩展知识点.md#ndk-开发-1)
       * [基础开发流程](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android扩展知识点.md#基础开发流程)
       * [System.loadLibrary()](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android扩展知识点.md#systemloadlibrary)
     * [CMake 构建 NDK 项目](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android扩展知识点.md#cmake-构建-ndk-项目)
     * [常用的 Android NDK 原生 API](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android扩展知识点.md#常用的-android-ndk-原生-api)
   * [类加载器](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android扩展知识点.md#类加载器)
     * [双亲委托模式](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android扩展知识点.md#双亲委托模式)
     * [DexPathList](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android扩展知识点.md#dexpathlist)


## Android 开源库源码分析

   * [LeakCanary](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android开源库源码分析.md#leakcanary)
     * [初始化注册](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android开源库源码分析.md#初始化注册)
     * [引用泄漏观察](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android开源库源码分析.md#引用泄漏观察)
     * [Dump Heap](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android开源库源码分析.md#dump-heap)
   * [EventBus](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android开源库源码分析.md#eventbus)
     * [自定义注解](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android开源库源码分析.md#自定义注解) 
     * [注册订阅者](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android开源库源码分析.md#注册订阅者) 
     * [发送事件](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Android开源库源码分析.md#发送事件) 

## 设计模式汇总 

   * [设计模式分类](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/设计模式汇总.md#设计模式分类)
   * [面向对象六大原则](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/设计模式汇总.md#面向对象六大原则)
   * [工厂模式](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/设计模式汇总.md#工厂模式)
   * [单例模式](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/设计模式汇总.md#单例模式)
   * [建造者模式](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/设计模式汇总.md#建造者模式)
   * [原型模式](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/设计模式汇总.md#原型模式)
   * [适配器模式](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/设计模式汇总.md#适配器模式)
   * [观察者模式](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/设计模式汇总.md#观察者模式)
   * [代理模式](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/设计模式汇总.md#代理模式)
   * [责任链模式](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/设计模式汇总.md#责任链模式)
   * [策略模式](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/设计模式汇总.md#策略模式)
   * [备忘录模式](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/设计模式汇总.md#备忘录模式)

## Gradle知识点汇总

   * [依赖项配置](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/Gradle知识点汇总.md#依赖项配置)

## 计算机网络基础

   * [网络体系的分层结构](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/计算机网络基础.md#网络体系的分层结构)
   * [HTTP 相关](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/计算机网络基础.md#http-相关)
     * [请求报文](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/计算机网络基础.md#请求报文)
       * [请求行](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/计算机网络基础.md#请求行)
       * [请求头](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/计算机网络基础.md#请求头)
     * [响应报文](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/计算机网络基础.md#响应报文)
     * [常见状态码](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/计算机网络基础.md#常见状态码)
     * [缓存机制](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/计算机网络基础.md#缓存机制)
     * [Https](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/计算机网络基础.md#https)
     * [Http 2.0](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/计算机网络基础.md#http-20)
   * [TCP/IP](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/计算机网络基础.md#tcpip)
     * [三次握手](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/计算机网络基础.md#三次握手)
     * [四次挥手](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/计算机网络基础.md#四次挥手)
     * [TCP 与 UDP 的区别](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/计算机网络基础.md#tcp-与-udp-的区别)
   * [Socket](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/计算机网络基础.md#socket)
     * [使用示例](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/计算机网络基础.md#使用示例)



## 常见面试算法题汇总

   * [排序](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#排序)
     * [比较排序](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#比较排序)
       * [冒泡排序](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#冒泡排序)
       * [归并排序](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#归并排序)
       * [快速排序](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#快速排序)
     * [线性排序](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#线性排序)
       * [计数排序](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#计数排序)
       * [桶排序](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#桶排序)
   * [二叉树](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#二叉树)
     * [顺序遍历](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#顺序遍历)
     * [层次遍历](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#层次遍历)
     * [左右翻转](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#左右翻转)
     * [最大值](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#最大值)
     * [最大深度](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#最大深度)
     * [最小深度](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#最小深度)
     * [平衡二叉树](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#平衡二叉树)
   * [链表](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#链表)
     * [删除节点](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#删除节点)
     * [翻转链表](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#翻转链表)
     * [中间元素](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#中间元素)
     * [判断是否为循环链表](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#判断是否为循环链表)
     * [合并两个已排序链表](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#合并两个已排序链表)
     * [链表排序](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#链表排序)
     * [删除倒数第N个节点](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#删除倒数第n个节点)
     * [两个链表是否相交](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#两个链表是否相交)
   * [栈 / 队列](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#栈--队列)
     * [带最小值操作的栈](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#带最小值操作的栈)
     * [有效括号](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#有效括号)
     * [用栈实现队列](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#用栈实现队列)
     * [逆波兰表达式求值](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#逆波兰表达式求值)
   * [二分](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#二分)
     * [二分搜索](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#二分搜索)
     * [X的平方根](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#x的平方根)
   * [哈希表](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#哈希表)
     * [两数之和](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#两数之和)
     * [连续数组](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#连续数组)
     * [最长无重复字符的子串](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#最长无重复字符的子串)
     * [最多点在一条直线上](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#最多点在一条直线上)
   * [堆 / 优先队列](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#堆--优先队列)
     * [前K大的数](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#前k大的数)
     * [前K大的数II](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#前k大的数ii)
     * [第K大的数](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#第k大的数)
   * [二叉搜索树](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#二叉搜索树)
     * [验证二叉搜索树](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#验证二叉搜索树)
     * [第K小的元素](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#第k小的元素)
   * [数组 / 双指针](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#数组--双指针)
     * [加一](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#加一)
     * [删除元素](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#删除元素)
     * [删除排序数组中的重复数字](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#删除排序数组中的重复数字)
     * [我的日程安排表 I](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#我的日程安排表-i)
     * [合并排序数组](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#合并排序数组)
   * [贪心](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#贪心)
     * [买卖股票的最佳时机](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#买卖股票的最佳时机)
     * [买卖股票的最佳时机 II](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#买卖股票的最佳时机-ii)
     * [最大子数组](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#最大子数组)
     * [主元素](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#主元素)
   * [字符串处理](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#字符串处理)
     * [生成括号](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#生成括号)
     * [Excel表列标题](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#excel表列标题)
     * [翻转游戏](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#翻转游戏)
     * [翻转字符串中的单词](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#翻转字符串中的单词)
     * [转换字符串到整数](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#转换字符串到整数)
     * [最长公共前缀](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#最长公共前缀)
     * [回文数](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#回文数)
   * [动态规划](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#动态规划)
     * [单词拆分](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#单词拆分)
     * [爬楼梯](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#爬楼梯)
     * [打劫房屋](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#打劫房屋)
     * [编辑距离](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#编辑距离)
     * [乘积最大子序列](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#乘积最大子序列)
   * [矩阵](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#矩阵)
     * [螺旋矩阵](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#螺旋矩阵)
     * [判断数独是否合法](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#判断数独是否合法)
     * [旋转图像](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#旋转图像)
   * [二进制 / 位运算](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#二进制--位运算)
     * [落单的数](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#落单的数)
     * [格雷编码](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#格雷编码)
   * [其他](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#其他)
     * [反转整数](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#反转整数)
     * [LRU缓存策略](https://github.com/CurvedBowZhang/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#lru缓存策略)
