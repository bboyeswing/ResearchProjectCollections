iOS 不错的第三方开源库归类分享
=================

前言
--

* * *

Github可说是全球最大的IT"交友约会"网站,各种各样牛逼的`open source code`,star!star!star!LZ逛github也有些时候了,经常会出现一个困惑,就是star了新的,很多以前star的一想不起名字,就很难找到,要一页一页的翻...想想,如果你star超过了50多页,每一次不得找死...之前我是用`Chrome`的收藏夹功能来区分,一段时间努力后,就成了下面这个样子:  


还是比较方便的,起码完成了分类,只是没能加上自己收藏时对链接的注释(这样查找更快了),昨天朋友推荐了[Astral](https://link.jianshu.com?t=https://app.astralapp.com/),通过加标签的方式来实现分类,也很直观明了...那为什么LZ还要做这个整理呢?一是,能够分享出来;二是:可以自己无限的加入自己解释,更快的`天下Code,唯快不破`查找_!

总览/大集合
------

* * *

*   [vsouza/awesome-ios](https://link.jianshu.com?t=https://github.com/vsouza/awesome-ios) (A curated list of awesome iOS ecosystem, including Objective-C and Swift Projects)
*   [matteocrippa/awesome-swift](https://link.jianshu.com?t=https://github.com/matteocrippa/awesome-swift#network) (A collaborative list of awesome swift resources. Feel free to contribute!)
*   [ipader/SwiftGuide](https://link.jianshu.com?t=https://github.com/ipader/SwiftGuide) (这份指南汇集了Swift语言主流学习资源，并以开发者的视角整理编排)
*   [ioscookies](https://link.jianshu.com?t=http://www.ioscookies.com/) (国外收集的优秀的swift第三方库)
*   [YYKit](https://link.jianshu.com?t=https://github.com/ibireme/YYKit) (涉及了图片下载,富文本,缓存等多个高性能开源库)
*   [JSPatch](https://link.jianshu.com?t=https://github.com/bang590/JSPatch) (js实现热更新,放这里是觉得它比较唯一,_)
*   [LeeGo](https://link.jianshu.com?t=https://github.com/wangshengjia/LeeGo) (LeeGo 是一个Swift框架，旨在带来更 声明式的，可配置的和易复用的UI开发方式，让UI开发变得像玩乐高积木一样简单直观，某种程度上取代ComponentKit)

网络请求Network
-----------

* * *

*   [AFNetworking](https://link.jianshu.com?t=https://github.com/AFNetworking/AFNetworking) (不解释了...都懂)
*   [Alamofire](https://link.jianshu.com?t=https://github.com/Alamofire/Alamofire) (swift版本AFNetworking)
*   [YTKNetwork](https://link.jianshu.com?t=https://github.com/yuantiku/YTKNetwork) (巧神团队封装了AFNetworking,本人现在的项目也在用)
*   [Pitaya](https://link.jianshu.com?t=https://github.com/johnlui/Pitaya) (支持 Basic Authorization、SSL 钢钉、HTTP raw body / JSON body、快速文件上传等特性，并通过内置 JSONNeverDie 实现了对 JSON 的完全支持)
*   [NetworkEye](https://link.jianshu.com?t=https://github.com/coderyi/NetworkEye) (可以监控App内HTTP请求并显示请求相关的详细信息，方便App开发的网络调试)

数据存储
----

* * *

*   [fmdb](https://link.jianshu.com?t=https://github.com/ccgus/fmdb) (不喜欢用coredata的人基本都会选它吧...)
*   [YTKKeyValueStore](https://link.jianshu.com?t=https://github.com/yuantiku/YTKKeyValueStore) (依旧是巧神团队力作)
*   [SQLite.swift](https://link.jianshu.com?t=https://github.com/stephencelis/SQLite.swift) (A type-safe, Swift-language layer over SQLite3.)
*   [GRDB.swift](https://link.jianshu.com?t=https://github.com/groue/GRDB.swift) (让操作 SQLite 再简单一点，方便、实用)
*   [realm-cocoa](https://link.jianshu.com?t=https://github.com/realm/realm-cocoa) (Realm主打移动数据库)
*   [CoreStore](https://link.jianshu.com?t=https://github.com/JohnEstropia/CoreStore) (Unleashing the real power of Core Data with the elegance and safety of Swift...没用过,看情形,swift有关coredata的开源库比sqlite的要多蛮多)
*   [SwiftyUserDefaults](https://link.jianshu.com?t=https://github.com/radex/SwiftyUserDefaults) (见名知意)
*   [AlecrimCoreData_Swift](https://link.jianshu.com?t=https://github.com/Alecrim/AlecrimCoreData)
*   [Pantry](https://link.jianshu.com?t=https://github.com/nickoneill/Pantry) (可以持久化基础类型（String, Int, Float, Bool）变量值的类库。无论是退出应用还是重启设备，持久化设置过的变量可以被保存下来)

图片异步下载缓存
--------

* * *

*   [SDWebImage](https://link.jianshu.com?t=https://github.com/rs/SDWebImage) (这个也不解释...源码很值得研究)
*   [PINRemoteImage](https://link.jianshu.com?t=https://github.com/pinterest/PINRemoteImage)
*   [Kingfisher](https://link.jianshu.com?t=https://github.com/onevcat/Kingfisher) (喵神作品,This project is heavily inspired by the popular SDWebImage)
*   [YYWebImage](https://link.jianshu.com?t=https://github.com/ibireme/YYWebImage) (支持 APNG、WebP、GIF 动图的异步加载与播放、编码与解码，支持渐进式图像加载)
*   [PHImageKit](https://link.jianshu.com?t=https://github.com/producthunt/PHImageKit) (出自 Product Hunter 开发小组的 带下载、缓存的 GIF 播放组件库)
*   [Nuke](https://link.jianshu.com?t=https://github.com/kean/Nuke) (Image loading, processing, caching and preheating)

json/HTML/XML<->model
---------------------

* * *

*   [JSONModel](https://link.jianshu.com?t=https://github.com/icanzilb/JSONModel) (可以好好研究下源码,LZ貌似还没在项目中用过)
*   [MJExtension](https://link.jianshu.com?t=https://github.com/CoderMJLee/MJExtension) (小码哥...)
*   [Mantle](https://link.jianshu.com?t=https://github.com/mantle/mantle)
*   [SwiftyJSON](https://link.jianshu.com?t=https://github.com/SwiftyJSON/SwiftyJSON) (The better way to deal with JSON data in Swift)
*   [JSONNeverDie](https://link.jianshu.com?t=https://github.com/johnlui/JSONNeverDie) (Auto reflection tool from JSON to Model, user friendly JSON encoder / decoder, aims to never die)
*   [JASON](https://link.jianshu.com?t=https://github.com/delba/JASON) (据说很高效)
*   [JSONCodable](https://link.jianshu.com?t=https://github.com/matthewcheok/JSONCodable) (Hassle-free JSON encoding and decoding in Swift)
*   [ObjectMapper](https://link.jianshu.com?t=https://github.com/Hearst-DD/ObjectMapper) (Simple JSON Object mapping written in Swift)
*   [Argo](https://link.jianshu.com?t=https://github.com/thoughtbot/Argo) (类似楼上,二选其一)
*   [YYModel](https://link.jianshu.com?t=https://github.com/ibireme/YYModel) (高性能,刚出不久,大家可以尝试一下,里面还有各个json-model库的性能测评)
*   [Ji](https://link.jianshu.com?t=https://github.com/honghaoz/Ji) (Ji (戟) is an XML/HTML parser for Swift)
*   [Kanna](https://link.jianshu.com?t=https://github.com/tid-kijyun/Kanna) (同上)
*   [Unbox](https://link.jianshu.com?t=https://github.com/JohnSundell/Unbox)

函数响应式编程框架
---------

* * *

*   [ReactiveCocoa](https://link.jianshu.com?t=https://github.com/ReactiveCocoa/ReactiveCocoa)
*   [RxSwift](https://link.jianshu.com?t=https://github.com/ReactiveX/RxSwift)
*   [PromiseKit_Swift](https://link.jianshu.com?t=https://github.com/mxcl/PromiseKit)
*   [Interstellar_Swift](https://link.jianshu.com?t=https://github.com/JensRavens/Interstellar) (极简的 FRP)
*   [Bond_Swift](https://link.jianshu.com?t=https://github.com/SwiftBond/Bond) (基于KVO)
*   [Observable_Swift](https://link.jianshu.com?t=https://github.com/slazyk/Observable-Swift) (KVO for Swift - Value Observing and Events)

Swift函数式编程
----------

* * *

*   [Dollar.swift](https://link.jianshu.com?t=https://github.com/ankurp/Dollar.swift) (提供了有用的函数式编程辅助方法，无需扩展任何内置对象。Dollar类似于Lo-Dash或者Javascript中的Underscore。)
*   [Swiftz](https://link.jianshu.com?t=https://github.com/typelift/Swiftz)

UI总览
----

* * *

*   [awesome-ios-ui](https://link.jianshu.com?t=https://github.com/cjwirth/awesome-ios-ui)
*   [fantastic-ios-animation](https://link.jianshu.com?t=https://github.com/onmyway133/fantastic-ios-animation) (基于 UI 组件类别分类，且带精彩动画效果的 iOS 组件库集合)
*   [FlatUIKit](https://link.jianshu.com?t=https://github.com/Grouper/FlatUIKit) (超喜欢这样的风格,强烈推荐)
*   [Material-Controls-For-iOS](https://link.jianshu.com?t=https://github.com/fpt-software/Material-Controls-For-iOS)
*   [iCarousel](https://link.jianshu.com?t=https://github.com/nicklockwood/iCarousel) (A simple, highly customisable, data-driven 3D carousel for iOS and Mac OS)

UINavigationController
----------------------

* * *

*   [navigation-stack](https://link.jianshu.com?t=https://github.com/Ramotion/navigation-stack) (入栈太深不好返回最初的vc,可以试试这个)

UIImagePickerController/图片浏览
----------------------------

* * *

*   [ZLPhotoLib](https://link.jianshu.com?t=https://github.com/MakeZL/ZLPhotoLib) (LZ项目中在用的,使用很方便)
*   [ZYQAssetPickerController](https://link.jianshu.com?t=https://github.com/heroims/ZYQAssetPickerController)
*   [UzysAssetsPickerController](https://link.jianshu.com?t=https://github.com/uzysjung/UzysAssetsPickerController)
*   [ImagePickerSheetController](https://link.jianshu.com?t=https://github.com/larcus94/ImagePickerSheetController)
*   [MLSwiftBasic](https://link.jianshu.com?t=https://github.com/MakeZL/MLSwiftBasic)
*   [PhotoBrowser](https://link.jianshu.com?t=https://github.com/CharlinFeng/PhotoBrowser)
*   [IDMPhotoBrowser](https://link.jianshu.com?t=https://github.com/ideaismobile/IDMPhotoBrowser) (功能比较完善的“图片浏览器”)
*   [ALCameraViewController_Swfit](https://link.jianshu.com?t=https://github.com/AlexLittlejohn/ALCameraViewController) (含可定制照片选择器，图片简单裁切功能)
*   [SKPhotoBrowser_Swift](https://link.jianshu.com?t=https://github.com/suzuki-0000/SKPhotoBrowser) (Simple PhotoBrowser/Viewer inspired by facebook, twitter photo browsers,based on IDMPhotoBrowser, MWPhotoBrowser 附带删除按钮)
*   [ImageViewer_Swift](https://link.jianshu.com?t=https://github.com/MailOnline/ImageViewer) (图片全屏预览组件及类库)
*   [BSImagePicker_Swift](https://link.jianshu.com?t=https://github.com/mikaoj/BSImagePicker) (图片多选控件)
*   [ImagePicker_Swift](https://link.jianshu.com?t=https://github.com/hyperoslo/ImagePicker) (图片多选控件)

UIScrollView
------------

* * *

*   [XXPagingScrollView](https://link.jianshu.com?t=https://github.com/adad184/XXPagingScrollView) (Paged scrollView with custom paging width)
*   [HACursor](https://link.jianshu.com?t=https://github.com/HAHAKea/HACursor) (是一个对横向ScrollView中的视图进行管理的UI控件。只要几行代码就可以集成类似于网易新闻对主题页面进行排序，删除操作的功能)
*   [GJAutoCycleScrollView](https://link.jianshu.com?t=https://github.com/devgj/GJAutoCycleScrollView) (一个自动循环滚动的滚动视图。只需要两张图片循环利用, 史上性能最佳。 支持网络图片)
*   [SDCycleScrollView](https://link.jianshu.com?t=https://github.com/gsdios/SDCycleScrollView) (无限循环图片轮播器)
*   [MediumScrollFullScreen](https://link.jianshu.com?t=https://github.com/pixyzehn/MediumScrollFullScreen) (滚动的时候隐藏导航栏和底部栏)
*   [SCNavigationControlCenter](https://link.jianshu.com?t=https://github.com/SergioChan/SCNavigationControlCenter) (类似于iOS9之后双击home出现的界面)
*   [APParallaxHeader](https://link.jianshu.com?t=https://github.com/apping/APParallaxHeader) (下拉head图片放大效果)

UILabel
-------

* * *

*   [LTMorphingLabel](https://link.jianshu.com?t=https://github.com/lexrus/LTMorphingLabel) (非常绚丽)
*   [UICountingLabel](https://link.jianshu.com?t=https://github.com/dataxpress/UICountingLabel) (数字动态变化,有动画效果)
*   [CharacterText](https://link.jianshu.com?t=https://github.com/android1989/CharacterText) (相比楼上,更简单实用)
*   [FolioReaderKit](https://link.jianshu.com?t=https://github.com/FolioReader/FolioReaderKit) (ePub 阅读器及解析框架类库)
*   [FNBlingBlingLabel](https://link.jianshu.com?t=https://github.com/Fnoz/FNBlingBlingLabel) (Swift实现的UILabel文字随机渐隐渐现, Swift版RQShineLabel.)

UIButton
--------

* * *

*   [CatZanButton](https://link.jianshu.com?t=https://github.com/K-cat/CatZanButton) (A animation button for "赞/Zan")
*   [DOFavoriteButton_swift](https://link.jianshu.com?t=https://github.com/okmr-d/DOFavoriteButton) (Cute Animated Button written in Swift.)
*   [TKAnimatedCheckButton](https://link.jianshu.com?t=https://github.com/entotsu/TKAnimatedCheckButton)
*   [LiquidFloatingActionButton](https://link.jianshu.com?t=https://github.com/yoavlt/LiquidFloatingActionButton) (会伸长的+)
*   [KYGooeyMenu](https://link.jianshu.com?t=https://github.com/KittenYang/KYGooeyMenu) (动画小王子KY出品,粘性弹出按钮,也可以作为UITabBarVC的中间按钮)
*   [XTNetReloader](https://link.jianshu.com?t=https://github.com/Akateason/XTNetReloader) (提示"没有wifi"的view和一个"重新加载"的button)
*   [ZFRippleButton](https://link.jianshu.com?t=https://github.com/zoonooz/ZFRippleButton) (点击button不同部位,出现不同的动画反应)
*   [SpreadButton_Swift](https://link.jianshu.com?t=https://github.com/liuzhiyi1992/SpreadButton) (一个当你点击它后会像花或者镰刀一样展开的按钮,你可以切换一种位置模式，把它当iphone里的AssistiveTouch.)
*   [NumberMorphView_Swift](https://link.jianshu.com?t=https://github.com/me-abhinav/NumberMorphView) (可爱的数字补间（变身）动画类库)
*   [SMSegmentView](https://link.jianshu.com?t=https://github.com/sima-11/SMSegmentView) (高可定制化，既支持横向，也支持纵向布局的图文 Segment Control 组件)

UITextField
-----------

* * *

*   [TextFieldEffects](https://link.jianshu.com?t=https://github.com/raulriera/TextFieldEffects) (Custom UITextFields effects inspired by Codrops, built using Swift)
*   [KeyboardMan](https://link.jianshu.com?t=https://github.com/nixzhu/KeyboardMan) (iOS8后键盘通知就不太正常了...)
*   [YYKeyboardManager](https://link.jianshu.com?t=https://github.com/ibireme/YYKeyboardManager) (YY键盘管理系列)
*   [TPKeyboardAvoiding](https://link.jianshu.com?t=https://github.com/michaeltyson/TPKeyboardAvoiding) (依旧是弹出键盘问题)
*   [FloatLabelFields](https://link.jianshu.com?t=https://github.com/FahimF/FloatLabelFields) ( 基于"Float Label Pattern"的内嵌浮动标签输入效果 Swift 版实现类库)
*   [SkyFloatingLabelTextField_Swift](https://link.jianshu.com?t=https://github.com/Skyscanner/SkyFloatingLabelTextField) (浮动标签输入库)
*   [PhoneNumberKit_Swift](https://link.jianshu.com?t=https://github.com/marmelroy/PhoneNumberKit) (针对于电话号码的特殊textfield)

UIImage/UIImageView
-------------------

* * *

*   [FLAnimatedImage](https://link.jianshu.com?t=https://github.com/Flipboard/FLAnimatedImage) (Performant animated GIF engine for iOS)
*   [ImageScout](https://link.jianshu.com?t=https://github.com/kaishin/ImageScout) (最小网络代价获得图片大小（宽和高）及类型，它对于很多场合，比如：布局和排版都有积极作用)
*   [gifu](https://link.jianshu.com?t=https://github.com/kaishin/gifu) (高性能 GIF 显示类库 Swift 版本)
*   [JWAnimatedImage](https://link.jianshu.com?t=https://github.com/wangjwchn/JWAnimatedImage) (集中了目前主流的 GIF 显示库的优点)
*   [SwiftyGif](https://link.jianshu.com?t=https://github.com/kirualex/SwiftyGif) (高性能 Gif 播放引擎。那么多 Gif 播放类库哪家强，这位同学的方案是与 @蚊子咬的包为什么那么圆 同学的 JWAnimatedImage 比比看，而 JWAnimatedImage 的方案是与 JWAFLAnimatedImage 比比看)

UITableView/UITableViewCell
---------------------------

* * *

*   [VVeboTableViewDemo](https://link.jianshu.com?t=https://github.com/johnil/VVeboTableViewDemo) (极致优化tableview...)
*   [SWTableViewCell](https://link.jianshu.com?t=https://github.com/CEWendel/SWTableViewCell) (An easy-to-use UITableViewCell subclass that implements a swippable content view which exposes utility buttons (similar to iOS 7 Mail Application))
*   [MGSwipeTableCell](https://link.jianshu.com?t=https://github.com/MortimerGoro/MGSwipeTableCell) (An easy to use UITableViewCell subclass that allows to display swippable buttons with a variety of transitions.)
*   [MMParallaxCell](https://link.jianshu.com?t=https://github.com/adad184/MMParallaxCell)
*   [Reusable](https://link.jianshu.com?t=https://github.com/AliSoftware/Reusable) (利用protocol extension结合泛型提供了一个优雅的方案来dequeueReusableCell.)

UICollectionView
----------------

* * *

*   [CSStickyHeaderFlowLayout](https://link.jianshu.com?t=https://github.com/jamztang/CSStickyHeaderFlowLayout) (UICollectionView replacement of UITableView. Do even more like Parallax Header, Sticky Section Header. Made for iOS 7. )
*   [LxGridView-swift](https://link.jianshu.com?t=https://github.com/DeveloperLx/LxGridView-swift) (Imitation iOS system desktop icon arrangement and interaction by UICollectionView!)
*   [CKWaveCollectionViewTransition](https://link.jianshu.com?t=https://github.com/CezaryKopacz/CKWaveCollectionViewTransition) (Cool wave like transition between two or more UICollectionView)
*   [StickyCollectionView](https://link.jianshu.com?t=https://github.com/matbeich/StickyCollectionView) (实现了 cell 在滚动时吸附在顶端并且之后的 cell 在其上方覆盖的效果)

UITabBarViewController
----------------------

* * *

*   [animated-tab-bar](https://link.jianshu.com?t=https://github.com/Ramotion/animated-tab-bar) (如名,animation\_tab\_bar)
*   [CYLTabBarController](https://link.jianshu.com?t=https://github.com/ChenYilong/CYLTabBarController)
*   [ESTabBarController_Swift](https://link.jianshu.com?t=https://github.com/eggswift/ESTabBarController) (高度自定义TabBarController，支持自定义TabBarItem样式或添加动画)

UINavigationBar
---------------

* * *

*   [AMScrollingNavbar](https://link.jianshu.com?t=https://github.com/andreamazz/AMScrollingNavbar)
*   [TLYShyNavBar](https://link.jianshu.com?t=https://github.com/telly/TLYShyNavBar)
*   [RainbowNavigation](https://link.jianshu.com?t=https://github.com/DanisFabric/RainbowNavigation) (UINavigationBar颜色变化的十分优秀的解决方案)
*   [KMNavigationBarTransition](https://link.jianshu.com?t=https://github.com/MoZhouqi/KMNavigationBarTransition) (过渡效果顺滑自然，你不用写一行代码,只用关心被 push 的 view controller 的导航栏的背景样式)

Left|Top_Menu
-------------

* * *

*   [PageMenu](https://link.jianshu.com?t=https://github.com/uacaps/PageMenu) (A paging menu controller built from other view controllers placed inside a scroll view (like Spotify, Windows Phone, Instagram),类似于网易,今日头条那种顶部菜单,下面滚动VC的控件)
*   [WMPageController](https://link.jianshu.com?t=https://github.com/wangmchn/WMPageController) (不知道这个库封装的如何,同事在项目中用了..感觉一般)
*   [YZDisplayViewController](https://link.jianshu.com?t=https://github.com/iThinkerYZ/YZDisplayViewController) (仿今日头条的页面切换,最近性能优化了一下)
*   [GuillotineMenu](https://link.jianshu.com?t=https://github.com/Yalantis/GuillotineMenu) (自定义push的Top菜单栏,刀砍式转场动画)
*   [BTNavigationDropdownMenu_Swift](https://link.jianshu.com?t=https://github.com/PhamBaTho/BTNavigationDropdownMenu) (在导航栏Title切换的菜单控件)
*   [Persei](https://link.jianshu.com?t=https://github.com/Yalantis/Persei) (Animated top menu for UITableView / UICollectionView / UIScrollView written in Swift )
*   [XLPagerTabStrip_Swift](https://link.jianshu.com?t=https://github.com/xmartlabs/XLPagerTabStrip) (Android PagerTabStrip for iOS.顶部菜单切换)
*   [SwipeViewController](https://link.jianshu.com?t=https://github.com/fortmarek/SwipeViewController/tree/2cb9383bf9a8dbf68be2d41c788bb53d18ff7ae8) (RKSwipeBetweenViewControllers - navigate between pages / ViewControllers)
*   [FlowingMenu_Swift](https://link.jianshu.com?t=https://github.com/yannickl/FlowingMenu) (弹簧式推出左侧菜单栏)
*   [DynamicMaskSegmentSwitch](https://link.jianshu.com?t=https://github.com/KittenYang/DynamicMaskSegmentSwitch) (可定制的SegmentUI)
*   [ARSegmentPager](https://link.jianshu.com?t=https://github.com/AugustRush/ARSegmentPager) (iOS 选项卡控制器)

Push/Present
------------

* * *

*   [FDFullscreenPopGesture](https://link.jianshu.com?t=https://github.com/forkingdog/FDFullscreenPopGesture#rd?sukey=cbbc36a2500a2e6c699bcaa2c3a2a4121c317876c7a2b222e5a82d353c00c6347c9f0f0036b4cf7fb377d54672c9869a) (纵享丝滑的手势操作...阳神出品)
*   [RMPZoomTransitionAnimator](https://link.jianshu.com?t=https://github.com/recruit-mp/RMPZoomTransitionAnimator) (A custom zooming transition animation for UIViewController)
*   [TKSubmitTransition](https://link.jianshu.com?t=https://github.com/entotsu/TKSubmitTransition) (Animated UIButton of Loading Animation and Transition Animation)
*   [BubbleTransition](https://link.jianshu.com?t=https://github.com/andreamazz/BubbleTransition)
*   [TransitionTreasury_Swift](https://link.jianshu.com?t=https://github.com/DianQK/TransitionTreasury) (各式转场动画,可以在[这里](https://link.jianshu.com?t=http://transitiontreasury.com/)查看他的gif效果图)

日历UI
----

* * *

*   [JTCalendar](https://link.jianshu.com?t=https://github.com/jonathantribouharet/JTCalendar)
*   [PDTSimpleCalendar](https://link.jianshu.com?t=https://github.com/jivesoftware/PDTSimpleCalendar)
*   [CVCalendar](https://link.jianshu.com?t=https://github.com/Mozharovsky/CVCalendar)
*   [Koyomi_Swfit](https://link.jianshu.com?t=https://github.com/shoheiyokoyama/Koyomi) (可定制 很强大)
*   [JTAppleCalendar_Swfit](https://link.jianshu.com?t=https://github.com/patchthecode/JTAppleCalendar)

UIWebView/WebViewController
---------------------------

* * *

*   [NJKWebViewProgress](https://link.jianshu.com?t=https://github.com/ninjinkun/NJKWebViewProgress)
*   [RNCachingURLProtocol](https://link.jianshu.com?t=https://github.com/rnapier/RNCachingURLProtocol)
*   [TOWebViewController](https://link.jianshu.com?t=https://github.com/TimOliver/TOWebViewController) (快速展示web页面的vc)

引导页/新手操作指示
----------

* * *

*   [Onboard](https://link.jianshu.com?t=https://github.com/mamaral/Onboard) (非常棒的引导页制作库)
*   [RazzleDazzle_swift](https://link.jianshu.com?t=https://github.com/IFTTT/RazzleDazzle) (A simple keyframe-based animation framework for iOS, written in Swift. Perfect for scrolling app intros.同上)
*   [KDIntroView](https://link.jianshu.com?t=https://github.com/likedan/KDIntroView)
*   [Presentation_swift](https://link.jianshu.com?t=https://github.com/hyperoslo/Presentation)
*   [BWWalkthrough](https://link.jianshu.com?t=https://github.com/ariok/BWWalkthrough) (a class to build custom walkthroughs for your iOS App)
*   [Instructions](https://link.jianshu.com?t=https://github.com/ephread/Instructions) (新功能指引页面)
*   [Gecco_Swift](https://link.jianshu.com?t=https://github.com/yukiasai/Gecco) (新功能指引页面)
*   [paper-onboarding_Swift](https://link.jianshu.com?t=https://github.com/Ramotion/paper-onboarding)

UIColor-颜色库
-----------

* * *

*   [DynamicColor_Swift](https://link.jianshu.com?t=https://github.com/yannickl/DynamicColor) (RGB颜色转换)
*   [Wonderful](https://link.jianshu.com?t=https://github.com/dsxNiubility/Wonderful) (一个非常好用的色彩库)
*   [BCColor_Swift](https://link.jianshu.com?t=https://github.com/boycechang/BCColor) (能够获取图片的颜色)

UI other 不知到咋分类了
----------------

* * *

*   [DKNightVersion](https://link.jianshu.com?t=https://github.com/Draveness/DKNightVersion) (白天/夜间模式切换)
*   [Koloda](https://link.jianshu.com?t=https://github.com/Yalantis/Koloda) (卡片式UIView)
*   [WZLBadge](https://link.jianshu.com?t=https://github.com/weng1250/WZLBadge) (一行代码搞定各种小红点)
*   [paper-switch](https://link.jianshu.com?t=https://github.com/Ramotion/paper-switch) (类库实现了当 Switch 组件开/关切换时，平滑过渡到父视图的变换效果功能（核心类继承了 UISwitch）)
*   [Whisper](https://link.jianshu.com?t=https://github.com/hyperoslo/Whisper) (使用简单、功能实用的消息及应用通知组件)
*   [CRToast](https://link.jianshu.com?t=https://github.com/cruffenach/CRToast) (从状态栏弹出消息提醒)
*   [LBTagView](https://link.jianshu.com?t=https://github.com/lovels/LBTagView) (添加标签视图)
*   [SKTagView](https://link.jianshu.com?t=https://github.com/zsk425/SKTagView) (标签视图,很不错,推荐一下)
*   [TKDotSegment](https://link.jianshu.com?t=https://github.com/TBXark/TKDotSegment) (不错的SegmentUI控件)
*   [PMAlertController](https://link.jianshu.com?t=https://github.com/Codeido/PMAlertController) (可定制弹窗组件替代官版不可定制的 UIAlertController)

AutoLayout
----------

* * *

*   [AutoLayout优秀的开源库](https://link.jianshu.com?t=http://www.hmttommy.com/2015/04/14/AutolayoutDetail/) (可以参考LZ之前写的这篇文章)
*   [Cartography](https://link.jianshu.com?t=https://github.com/robb/Cartography)
*   [EasyPeasy_Swift](https://link.jianshu.com?t=https://github.com/nakiostudio/EasyPeasy)
*   [Neon](https://link.jianshu.com?t=https://github.com/mamaral/Neon)
*   [FDStackView](https://link.jianshu.com?t=https://github.com/forkingdog/FDStackView) (这个项目通过巧妙的方式用自己的一套实现在非 iOS 9 中替换了 UIStackView 的链接和实现，让我们可以在低至 iOS 6 的系统上使用UIStackView，并且保持和最新的 iOS 9 上同样的用法和语法)
*   [AutolayoutExampleWithMasonry](https://link.jianshu.com?t=https://github.com/zekunyan/AutolayoutExampleWithMasonry) (有一系列的文章来讲明使用)
*   [Stevia](https://link.jianshu.com?t=https://github.com/s4cha/Stevia) (简单、直观的纯代码自动布局类库,可以玩玩)
*   [SDAutoLayout](https://link.jianshu.com?t=https://github.com/gsdios/SDAutoLayout) (例子比较丰富..仿微信朋友圈等)

Pop-up/Pop-down View
--------------------

* * *

*   [DOPDropDownMenu-Enhanced](https://link.jianshu.com?t=https://github.com/12207480/DOPDropDownMenu-Enhanced) (类似美团的下拉选择菜单)
*   [JSDropDownMenu](https://link.jianshu.com?t=https://github.com/jsfu/JSDropDownMenu)
*   [DropdownListView](https://link.jianshu.com?t=http://code.cocoachina.com/detail/315440/DropdownListView)
*   [kxmenu](https://link.jianshu.com?t=https://github.com/kolyvan/kxmenu) (举例:点击微信app上的那个"+"弹出的视图)
*   [NirKxMenu_swift](https://link.jianshu.com?t=https://github.com/zpz1237/NirKxMenu) (同上)
*   [MMPopupView](https://link.jianshu.com?t=https://github.com/adad184/MMPopupView) (Pop-up based view(e.g. alert sheet), can easily customize.)
*   [DXAlertView](https://link.jianshu.com?t=https://github.com/xiekw2010/DXAlertView) (自定义动画效果的alertview,实现还是比较简单的)
*   [SCLAlertView-Swift](https://link.jianshu.com?t=https://github.com/vikmeup/SCLAlertView-Swift) (Beautiful animated Alert View. Written in Swift)
*   [SweetAlert-iOS](https://link.jianshu.com?t=https://github.com/codestergit/SweetAlert-iOS) (Live animated Alert View for iOS written in Swift)
*   [PSTAlertController](https://link.jianshu.com?t=https://github.com/steipete/PSTAlertController) (兼容 iOS7的 XXAlertController，接口跟UIAlertController 一模一样，高低版本通用--另外这个作者可以follow一下,_)
*   [JDStatusBarNotification](https://link.jianshu.com?t=https://github.com/jaydee3/JDStatusBarNotification) (呈现在状态栏的通知视图)
*   [BHBPopView](https://link.jianshu.com?t=https://github.com/bb-coder/BHBPopView)/[PopMenu](https://link.jianshu.com?t=https://github.com/xhzengAIB/PopMenu)/[SinaWeiboLikeMenu](https://link.jianshu.com?t=https://github.com/SmallBlackCat/SinaWeiboLikeMenu) (仿新浪微博点击"+"弹出的效果)

下拉刷新和上拉加载
---------

* * *

*   [MJRefresh](https://link.jianshu.com?t=https://github.com/CoderMJLee/MJRefresh) (不得不说,小码哥的另一个好用的code)
*   [CBStoreHouseRefreshControl](https://link.jianshu.com?t=https://github.com/coolbeet/CBStoreHouseRefreshControl) (第一感觉就是,会玩)
*   [PullToRefreshCoreText](https://link.jianshu.com?t=https://github.com/cemolcay/PullToRefreshCoreText) (半塘下拉刷新效果,refresh效果类似今日头条,不难实现)
*   [Pull-to-Refresh.Rentals](https://link.jianshu.com?t=https://github.com/Yalantis/Pull-to-Refresh.Rentals-iOS)
*   [PullToBounce_swift](https://link.jianshu.com?t=https://github.com/entotsu/PullToBounce) (Animated "Pull To Refresh" Library for UIScrollView)
*   [PullToMakeSoup_swift](https://link.jianshu.com?t=https://github.com/Yalantis/PullToMakeSoup) (水煮沸动画...)
*   [PullToRefreshSwift](https://link.jianshu.com?t=https://github.com/dekatotoro/PullToRefreshSwift)
*   [DGElasticPullToRefresh](https://link.jianshu.com?t=https://github.com/gontovnik/DGElasticPullToRefresh) (皮筋式的下拉刷新动画)
*   [refresher_Swift](https://link.jianshu.com?t=https://github.com/jcavar/refresher) (一个常用的下拉即刷新列表工具类，提供开放接口定制刷新动态变换效果)
*   [Infinity_Swift](https://link.jianshu.com?t=https://github.com/DanisFabric/Infinity) (完全支持自定义交互动画,一句话代码集成)
*   [PeriscopyPullToRefresh](https://link.jianshu.com?t=https://github.com/anaglik/PeriscopyPullToRefresh) (UINavigationBar刷新变化)
*   [pull-to-refresh_Swift](https://link.jianshu.com?t=https://github.com/eggswift/pull-to-refresh) (通过一个 UIScrollView 的扩展，可以轻松为 UIScrollView 的所有子类添加下拉刷新功能)
*   [FNMatchPull](https://link.jianshu.com?t=https://github.com/Fnoz/FNMatchPull) (Swift实现的火柴图案&火柴文字下拉刷新动效)

Animation
---------

* * *

*   [awesome-ios-animation](https://link.jianshu.com?t=https://github.com/sxyx2008/awesome-ios-animation) (A curated list of awesome iOS animation, including Objective-C and Swift libraries)
*   [Animatious Group](https://link.jianshu.com?t=https://github.com/Animatious/awesome-animation)
*   [facebook/pop](https://link.jianshu.com?t=https://github.com/facebook/pop) (facebook出品,必属精品)
*   [Spring_Swift](https://link.jianshu.com?t=https://github.com/MengTo/Spring)
*   [KittenYang/Animations](https://link.jianshu.com?t=https://github.com/KittenYang/Animations) (动画小王子KittenYang,最近他还出了一本书,LZ也买了,很不错,研读中)
*   [JHChainableAnimations](https://link.jianshu.com?t=https://github.com/jhurray/JHChainableAnimations) (类masonry的链式语法,棒棒哒)
*   [DKChainableAnimationKit_swift](https://link.jianshu.com?t=https://github.com/Draveness/DKChainableAnimationKit) (同上,swift版本)
*   [Cheetah](https://link.jianshu.com?t=https://github.com/suguru/Cheetah) (Easy animation library on iOS with Swift2)
*   [DCAnimationKit](https://link.jianshu.com?t=https://github.com/daltoniam/DCAnimationKit) (A collection of animations for iOS. Simple, just add water animations.)
*   [EasyAnimation](https://link.jianshu.com?t=https://github.com/icanzilb/EasyAnimation)
*   [WaterWave](https://link.jianshu.com?t=https://github.com/search?utf8=%E2%9C%93&q=WaterWave) (水波纹效果)
*   [PulsingHalo](https://link.jianshu.com?t=https://github.com/shu223/PulsingHalo) (水涟漪动画)
*   [IBAnimatable](https://link.jianshu.com?t=https://github.com/JakeLin/IBAnimatable) (支持在Interface Builder上配置个性化换场动画和手势)

图表/进度条/Loading/K线
-----------------

* * *

*   [aswesome-iOS-chart](https://link.jianshu.com?t=https://github.com/sxyx2008/awesome-ios-chart) (A curated list of awesome iOS chart libraries, including Objective-C and Swift...排在第一个的就是`PNChart`)
*   [Scrollable-GraphView](https://link.jianshu.com?t=https://github.com/philackm/Scrollable-GraphView) (灵动感十足的自适应、可定制滚动曲（折）线图表库)
*   [ios-charts](https://link.jianshu.com?t=https://github.com/danielgindi/ios-charts) (Android 图表开源库 MPAndroidChart 的 Swift 版)
*   [MBCircularProgressBar](https://link.jianshu.com?t=https://github.com/matibot/MBCircularProgressBar) (2/3圆进度条)
*   [TYWaterWaveView](https://link.jianshu.com?t=https://github.com/12207480/TYWaterWaveView) (水波圆形进度控件)
*   [Graphs_Swift](https://link.jianshu.com?t=https://github.com/recruit-mtl/Graphs) (非常易用的轻量级图表绘制库)
*   [core-plot](https://link.jianshu.com?t=https://github.com/core-plot/core-plot)
*   [MRProgress](https://link.jianshu.com?t=https://github.com/mrackwitz/MRProgress) (Collection of iOS drop-in components to visualize progress)
*   [UAProgressView](https://link.jianshu.com?t=https://github.com/UrbanApps/UAProgressView) (UAProgressView is a simple and lightweight, yet powerful animated circular progress view)
*   [Win7LoadingBar](https://link.jianshu.com?t=https://github.com/PowerAuras/Win7LoadingBar) (ios上的windows7风格的进度条)
*   [YLProgressBar](https://link.jianshu.com?t=https://github.com/YannickL/YLProgressBar) (UIProgressView replacement with an highly and fully customizable animated progress bar in pure Core Graphics)
*   [WSProgressHUD](https://link.jianshu.com?t=https://github.com/devSC/WSProgressHUD) (举例:loading...加载中...等进度蒙层)
*   [MBProgressHUD](https://link.jianshu.com?t=https://github.com/jdg/MBProgressHUD) (同上,比较火,很多app都用到了,当然有时间还是自定义好)
*   [APESuperHUD](https://link.jianshu.com?t=https://github.com/apegroup/APESuperHUD) (Swift的一个hud加载)
*   [SCCatWaitingHUD](https://link.jianshu.com?t=https://github.com/SergioChan/SCCatWaitingHUD) (可爱的动画loading...)
*   [RWBarChartView](https://link.jianshu.com?t=https://github.com/eternityz/RWBarChartView) (能够滑动的支柱形图表)
*   [FeSpinner](https://link.jianshu.com?t=https://github.com/NghiaTranUIT/FeSpinner) (各种Loading动画)
*   [FillableLoaders](https://link.jianshu.com?t=https://github.com/poolqf/FillableLoaders) (灌水加载动画....)
*   [WaveLoadingView](https://link.jianshu.com?t=https://github.com/liuzhiyi1992/WaveLoadingView) (圆形波浪进度指示器类及演示（可配置参数丰富）)
*   [EZLoadingActivity](https://link.jianshu.com?t=https://github.com/goktugyil/EZLoadingActivity) (适配了Swift3.0 的加载loading view)
*   [NVActivityIndicatorView](https://link.jianshu.com?t=https://github.com/ninjaprox/NVActivityIndicatorView) (Collection of nice loading animations)
*   [Y_KLine](https://link.jianshu.com?t=https://github.com/WillkYang/Y_KLine)(iOS专业K线第一版：K线主副图、趋势图、成交量、滚动、放大缩小、MACD、KDJ等)
*   [YYStock](https://link.jianshu.com?t=https://github.com/WillkYang/YYStock) (整合了分时图，日周月K线图，五档图，长按，捏合缩放，全屏非全屏切换自适应 )

CoreText
--------

* * *

*   [TTTAttributedLabel](https://link.jianshu.com?t=https://github.com/TTTAttributedLabel/TTTAttributedLabel) (图文混排...超链接...iOS7之后有了Textkit)
*   [TYAttributedLabel](https://link.jianshu.com?t=https://github.com/12207480/TYAttributedLabel) (LZ项目用它,还解决了"截断"问题,类似于appstore介绍的"..更多")
*   [MLEmojiLabel](https://link.jianshu.com?t=https://github.com/molon/MLEmojiLabel) (微信类似的自动识别网址号码邮箱和表情的label)
*   [GCD_Label](https://link.jianshu.com?t=https://github.com/johnil/GCD_Label)
*   [YYText](https://link.jianshu.com?t=https://github.com/ibireme/YYText)
*   [ActiveLabel.swift](https://link.jianshu.com?t=https://github.com/optonaut/ActiveLabel.swift) (UILabel drop-in replacement supporting Hashtags (#), Mentions (@) and URLs (http://) written in Swift)
*   [HYLabel_Swift](https://link.jianshu.com?t=https://github.com/coderwhy/HYLabel) (用于识别Label中的@用户-话题##-链接)
*   [TextAttributes_Swfit](https://link.jianshu.com?t=https://github.com/delba/TextAttributes) (链式语法,设置 UILabel 显示格式更容易)
*   [SwiftyAttributes](https://link.jianshu.com?t=https://github.com/eddiekaiger/SwiftyAttributes) (处理 AttributedString 的链式语法,非常方便)
*   [Attributed](https://link.jianshu.com?t=https://github.com/Nirma/Attributed) (同上)

音频视频
----

* * *

*   [bilibili](https://link.jianshu.com?t=https://github.com/bilibili)
*   [KRVideoPlayer](https://link.jianshu.com?t=https://github.com/36Kr-Mobile/KRVideoPlayer) (类似Weico的播放器，支持竖屏模式下全屏播放)
*   [DOUAudioStreamer](https://link.jianshu.com?t=https://github.com/douban/DOUAudioStreamer)
*   [SBVideoCaptureDemo](https://link.jianshu.com?t=https://github.com/PandaraWen/SBVideoCaptureDemo)
*   [ESTMusicPlayer](https://link.jianshu.com?t=https://github.com/Aufree/ESTMusicPlayer) (类似于网易云音乐的完整Demo,值得一看)
*   [KRVideoPlayer](https://link.jianshu.com?t=https://github.com/36Kr-Mobile/KRVideoPlayer) (类似Weico的播放器，支持竖屏模式下全屏播放)
*   [TheAmazingAudioEngine](https://link.jianshu.com?t=https://github.com/TheAmazingAudioEngine/TheAmazingAudioEngine) (很多音频类APP应用这个框架作开发)
*   [movielala](https://link.jianshu.com?t=https://github.com/movielala) (TVOS以及视频类的可以关注一下这几个作者)
*   [VideoSplashKit_Swift](https://link.jianshu.com?t=https://github.com/movielala/VideoSplashKit) (登录页面播放视频的制作)
*   [ZFPlayer](https://link.jianshu.com?t=https://github.com/renzifeng/ZFPlayer) (基于AVPlayer，支持横屏、竖屏（全屏播放还可锁定屏幕方向），上下滑动调节音量、屏幕亮度，左右滑动调节播放进度)

GCD/Notification
----------------

* * *

*   [RunKit](https://link.jianshu.com?t=https://github.com/khoiln/RunKit) (针对GCD框架的一个友好访问封装库,支持方法链式调用)
*   [Async](https://link.jianshu.com?t=https://github.com/duemunk/Async) (Syntactic sugar in Swift for asynchronous dispatches in Grand Central Dispatch,封装了系统的GCD,提供的接口简洁方便)
*   [SwiftNotificationCenter](https://link.jianshu.com?t=https://github.com/100mango/SwiftNotificationCenter) (基于协议的通知中心)

String/CGFloat/Int/Double
-------------------------

* * *

*   [Format](https://link.jianshu.com?t=https://github.com/marmelroy/Format) (针对数字、货币、地址及颜色的格式化工具库)
*   [Surge](https://link.jianshu.com?t=https://github.com/mattt/Surge) (基于苹果 Accelerate 高性能计算框架库，计算效率提升惊人)
*   [SwiftString](https://link.jianshu.com?t=https://github.com/amayne/SwiftString) (这款 String 扩展功能很丰富,无论格式化杂乱字符串，还是子串查找，亦或是格式转换都很强大)

Date
----

* * *

*   [SwiftDate](https://link.jianshu.com?t=https://github.com/malcommac/SwiftDate) (特别完整、强大的日期操作管理类库。它几乎涵盖了已知开源日期类库所有优秀特性)
*   [SwiftMoment](https://link.jianshu.com?t=https://github.com/akosma/SwiftMoment) (时间和日历函数封装库)

Categories
----------

* * *

*   [iOS-Categories](https://link.jianshu.com?t=https://github.com/shaojiankui/IOS-Categories) (iOS中的各种Objective-C Category, a collection of useful Objective-C Categories extending iOS Frameworks such as Foundation,UIKit,CoreData,QuartzCore,CoreLocation,MapKit Etc.)
*   [EZSwiftExtensions](https://link.jianshu.com?t=https://github.com/goktugyil/EZSwiftExtensions) (同上swift版本)
*   [ExSwift](https://link.jianshu.com?t=https://github.com/pNre/ExSwift) (同上,很久没更新了,在Swift2.0中各种报错)
*   [UITableView-FDTemplateLayoutCell](https://link.jianshu.com?t=https://github.com/forkingdog/UITableView-FDTemplateLayoutCell) (阳神出品,cell动态高度必备,就算你不支持iOS7,iOS8+虽可以自动计算高度,但重复计算cell高度也会让你需要用到的)
*   [ESSeparatorInset](https://link.jianshu.com?t=https://github.com/EnjoySR/ESSeparatorInset) (一行代码移除 UITableView 分割线左边的默认的间距)
*   [SwiftDate](https://link.jianshu.com?t=https://github.com/malcommac/SwiftDate) (Easy NSDate Management in Swift)
*   [SigmaSwiftStatistics](https://link.jianshu.com?t=https://github.com/evgenyneu/SigmaSwiftStatistics) (各种数学计算)
*   [jrswizzle](https://link.jianshu.com?t=https://github.com/rentzsch/jrswizzle) (method swizzling 很简便)

Tools
-----

* * *

*   [iOS-Runtime-Headers](https://link.jianshu.com?t=https://github.com/nst/iOS-Runtime-Headers) (查找那些方法属于publie/private/dylib)
*   [PleaseBaoMe](https://link.jianshu.com?t=https://github.com/callmewhy/PleaseBaoMe) (A useful tool to view SQLite file in Web browser during app running procedure.)
*   [xctool](https://link.jianshu.com?t=https://github.com/facebook/xctool) (自动打包)
*   [xcode-snippets](https://link.jianshu.com?t=https://github.com/Abizern/xcode-snippets) (代码块,比如你需要经常写tableview的代理方法,可以把他们做成你常用的代码块)
*   [Proposer_Swift](https://link.jianshu.com?t=https://github.com/nixzhu/Proposer) (它能以单个 API 处理 iOS 上的权限请求，以便使用前确认可访问“相册”、“相机”、“麦克风”、“通讯录”或“用户位置”。)
*   [Permission_Swift](https://link.jianshu.com?t=https://github.com/delba/Permission) (统一的 API 请求 iOS 本地设备及资源权限类库)
*   [FlagKit](https://link.jianshu.com?t=https://github.com/madebybowtie/FlagKit) (这个库包含了设计漂亮，风格统一的一套旗帜，并且按照国家代码进行了编排，使得我们可以很容易地使用用户设备语言来选择和显示对应的旗帜，十分方便)
*   [CryptoSwift](https://link.jianshu.com?t=https://github.com/krzyzanowskim/CryptoSwift) (纯swift写的"MD5","BASE64"等加密库)
*   [BeautyAddressBook](https://link.jianshu.com?t=https://github.com/hackxhj/BeautyAddressBook) (通讯录...)
*   [Facebook Tweaks](https://link.jianshu.com?t=https://github.com/facebook/Tweaks) (不需要重复编译微调UI和动画)
*   [R.swift](https://link.jianshu.com?t=https://github.com/mac-cain13/R.swift) (Get strong typed, autocompleted resources like images, fonts and segues in Swift projects,谁用谁知道)
*   [SwiftGen](https://link.jianshu.com?t=https://github.com/AliSoftware/SwiftGen) (A collection of Swift tools to generate Swift code (enums for your assets, storyboards, Localizable.strings, …))
*   [Shark_swift](https://link.jianshu.com?t=https://github.com/kaandedeoglu/Shark) (Swift Script that transforms the .xcassets folder into a type safe enum)
*   [SwiftyBeaver](https://link.jianshu.com?t=https://github.com/SwiftyBeaver/SwiftyBeaver) (log日志输出,颜色变换/快速)
*   [LxDBAnything](https://link.jianshu.com?t=https://github.com/DeveloperLx/LxDBAnything) (log日志输出,非常的直观和好用)
*   [SwiftVerbalExpressions](https://link.jianshu.com?t=https://github.com/VerbalExpressions/SwiftVerbalExpressions) (有助于构建困难的正则表达式-从令人敬畏的 JavaScript VerbalExpressions 移植过来)
*   [Every.swift](https://link.jianshu.com?t=https://github.com/samhann/Every.swift) (封装的定时器库,使用很便捷)
*   [Localize-Swift](https://link.jianshu.com?t=https://github.com/marmelroy/Localize-Swift) (国际化设定,很好用的库)
*   [FBRetainCycleDetector](https://link.jianshu.com?t=https://github.com/facebook/FBRetainCycleDetector) (iOS library to help detecting retain cycles in runtime.)

Unit Testing
------------

* * *

*   [Quick](https://link.jianshu.com?t=https://github.com/Quick/Quick)(用于Swift中的单元测试)
*   [Kiwi](https://link.jianshu.com?t=https://github.com/kiwi-bdd/Kiwi)(objective-c语言的测试框架，最流行的BDD测试框架)
*   [KIF](https://link.jianshu.com?t=https://github.com/kif-framework/KIF) (一个开源的用户界面UI测试框架. 使用 KIF, 并利用 iOS中的辅助功能 API, 你将能够编写模拟用户输入，诸如点击，触摸和文本输入，自动化的UI测试.)
*   [specta](https://link.jianshu.com?t=https://github.com/specta/specta) (objective-c语言的测试框架，用的人多)

网络状况监测
------

* * *

*   [Reachability](https://link.jianshu.com?t=https://github.com/tonymillion/Reachability)
*   [Reachability.swift](https://link.jianshu.com?t=https://github.com/ashleymills/Reachability.swift)
*   [SSASwiftReachability](https://link.jianshu.com?t=https://github.com/SSA111/SSASwiftReachability)

keychain
--------

* * *

*   [Locksmith_swift](https://link.jianshu.com?t=https://github.com/matthewpalmer/Locksmith)
*   [sskeychain](https://link.jianshu.com?t=https://github.com/soffes/sskeychain)

Xcode 插件
--------

* * *

*   [Alcatraz](https://link.jianshu.com?t=https://github.com/supermarin/Alcatraz) (Package manager for Xcode,有它装插件实在是太方便了)
*   [RTImageAssets](https://link.jianshu.com?t=https://github.com/rickytan/RTImageAssets) (A Xcode plugin to automatically generate @2x, @1x image from @3x image for you, or upscale to @3x from @2x)
*   [FuzzyAutocompletePlugin](https://link.jianshu.com?t=https://github.com/FuzzyAutocomplete/FuzzyAutocompletePlugin) (没它都不会写代码了...不过XCode7.3自带了...)
*   [ClangFormat-Xcode](https://link.jianshu.com?t=https://github.com/travisjeffery/ClangFormat-Xcode) (Xcode plug-in to to use clang-format from in Xcode and consistently format your code with Clang)
*   [ZLGotoSandboxPlugin](https://link.jianshu.com?t=https://github.com/MakeZL/ZLGotoSandboxPlugin) (从xcode中快速跳转到沙盒)
*   [SBShortcutMenuSimulator](https://link.jianshu.com?t=https://github.com/DeskConnect/SBShortcutMenuSimulator) (3D Touch shortcuts in the Simulator)
*   [ESJsonFormat-Xcode](https://link.jianshu.com?t=https://github.com/EnjoySR/ESJsonFormat-Xcode) (将JSON格式化输出为模型的属性,配合MJExtension很nice)
*   [JSONExport](https://link.jianshu.com?t=https://github.com/Ahmed-Ali/JSONExport) (JSON格式转objc,swfit等格式model)
*   [Peckham](https://link.jianshu.com?t=https://github.com/markohlebar/Peckham) (快捷引入头文件)
*   [injectionforxcode](https://link.jianshu.com?t=https://github.com/johnno1962/injectionforxcode) (超级强烈的推荐,只需要ctl+=你就能刷新改动代码效果)
*   [FLEX](https://link.jianshu.com?t=https://github.com/Flipboard/FLEX) (LLDB式的调试工具,界面可视化)
*   [JSPatchX](https://link.jianshu.com?t=https://github.com/bang590/JSPatchX) (如其名)

mac 插件
------

* * *

*   [Cakebrew](https://link.jianshu.com?t=https://github.com/brunophilipe/Cakebrew) ( Homebrew 量身定做的图形界面应用, 可以方便你查看 Homebrew 下载过的软件包具体信息, 并可对其进行安装, 卸载等操作)

书籍
--

* * *

*   [禅与 Objective-C 编程艺术](https://link.jianshu.com?t=https://github.com/oa414/objc-zen-book-cn)
*   [the-swift-programming-language-in-chinese](https://link.jianshu.com?t=https://github.com/numbbbbb/the-swift-programming-language-in-chinese)
*   [Producter - 让产品从 0 到 1](https://link.jianshu.com?t=https://selfstore.io/products/367)
*   [iOS Core Animation: Advanced Techniques中文译本](https://link.jianshu.com?t=https://zsisme.gitbooks.io/ios-/content/index.html)
*   [iOS9适配系列教程](https://link.jianshu.com?t=https://github.com/ChenYilong/iOS9AdaptationTips)
*   [ParseSourceCodeStudy](https://link.jianshu.com?t=https://github.com/ChenYilong/ParseSourceCodeStudy) (Facebook开源的Parse源码分析系列)
*   [全栈增长工程师指南](https://link.jianshu.com?t=https://github.com/phodal/growth-ebook)
*   [summary of Apple's Swift language written on Playgrounds](https://link.jianshu.com?t=https://github.com/jakarmy/swift-summary)
*   [李智维的PPT分享](https://link.jianshu.com?t=https://github.com/lzwjava/Keynotes) (涉及单元测试和WebSocket)
*   [MShare分享会资料](https://link.jianshu.com?t=https://github.com/mengxiangyue/MShare_Salon)
*   [LearnRxSwift](https://link.jianshu.com?t=https://github.com/DianQK/LearnRxSwift) (淀青的RxSwift教学)

他人推荐
----

* * *

*   [个人常用iOS第三方库以及XCode插件介绍](https://link.jianshu.com?t=http://adad184.com/2015/07/08/my-favorite-libraries-and-plugins/?sukey=66d4519b2d3854cd422400f82849a2def4b7516bcbc0e3feb93a32fa2ca3a878d283f32c9fce64cafc475ed52b8b6097)
*   [iOS第三方开源库的吐槽和备忘](https://link.jianshu.com?t=http://www.cocoachina.com/ios/20140123/7746.html)
*   [公司用到的一些 iOS 开源库和第三方组件](https://www.jianshu.com/p/207a3879c41f)
*   [Github 上的 iOS 开源项目](https://link.jianshu.com?t=http://ios.jobbole.com/84684/)
*   [Facebook Paper使用的第三方库](https://link.jianshu.com?t=http://blog.rpplusplus.me/blog/2014/02/11/facebook-paper-used-3rd/)
*   [thirdToos](https://link.jianshu.com?t=http://rookie.org.cn/2015/07/16/thirdToos/) (妹子..)
*   [27个iOS常用开发库](https://link.jianshu.com?t=https://medium.com/app-coder-io/27-ios-open-source-libraries-to-skyrocket-your-development-301b67d3124c)
*   [Github上关于iOS的各种开源项目集合-总有一款适合你](https://www.jianshu.com/p/801519f90a37)

完整的开源项目
-------

* * *

*   [Yep_Swift](https://link.jianshu.com?t=https://github.com/CatchChat/Yep) (凯文周新作,纯Swift)
*   [Coding-iOS](https://link.jianshu.com?t=https://github.com/Coding/Coding-iOS) (Coding-iOS 客户端)
*   [phphub-ios](https://link.jianshu.com?t=https://github.com/Aufree/phphub-ios) (phphub-ios 客户端)
*   [仿半塘App](https://link.jianshu.com?t=https://github.com/Ryan0520/BTApp)
*   [TSWeChat_Swfit](https://link.jianshu.com?t=https://github.com/hilen/TSWeChat) (swift仿写微信客户端)
*   [ZFZhiHuDaily_Swift](https://link.jianshu.com?t=https://github.com/renzifeng/ZFZhiHuDaily) (知乎日报仿写)
*   [30DaysofSwift](https://link.jianshu.com?t=https://github.com/allenwong/30DaysofSwift) (30天30个小demo)
*   [MessageDisplayKit](https://link.jianshu.com?t=https://github.com/xhzengAIB/MessageDisplayKit) (仿微信的app)
*   [react-native-gitfeed](https://link.jianshu.com?t=https://github.com/xiekw2010/react-native-gitfeed) (Yet another Github client written with react-native.)
*   [jchat-swift](https://link.jianshu.com?t=https://github.com/jpush/jchat-swift) (简单几步，换一个logo和名字即可拥有自己的IM)

