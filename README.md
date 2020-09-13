flutter_app_packages
记录 flutter 比较好的包

pubspec.yaml 文件

intl: ^0.16.0  
 dio: ^3.0.3  
 provider: ^3.0.0+1  
 provider_architecture: 1.0.3

- A set of widgets to help with the implementation of the FilledStacks Provider Architecture

shared_preferences: ^0.5.1+1  
 cached_network_image: ^0.7.0  
 fluttertoast: ^3.0.3  
 flukit: ^1.0.2

camera: ^0.5.8+2  
 image_picker: ^0.6.7+4  
 path_provider: ^1.6.11  
 video_player: ^0.10.11+2

- The following adds the Cupertino Icons font to your application.
  Use with the CupertinoIcons class for iOS style icons.

cupertino_icons: ^0.1.3  
 url_launcher: ^5.4.2  
 flutter_html_view: any  
 flutter_html_textview: any  
 flutter_html_textview: 0.2.5

flutter_markdown: ^0.4.2  
 html2md: 0.3.1  
 platform_aware: ^0.4.0  
 native_widgets: 1.0.0+2 ^1.3.7+1  
 flutter_calendar: ^0.0.9  
 calendarro: ^1.2.0  
 flutter_picker: ^1.1.5  
 flutter_datetime_picker: ^1.3.8  
 flutter_colorpicker: ^0.3.4  
 webview_flutter: ^0.3.22+1  
 flutter_webview_plugin: ^0.3.11  
 syncfusion_flutter_charts: ^18.2.46  
 flutter_echarts: ^1.3.5  
 fl_chart: ^0.11.0  
 charts_flutter: ^0.8.1  
 permission_handler: ^5.0.1+1  
 oktoast: ^2.3.1+1  
 barcode_scan: ^3.0.1  
 flutter_barcode_scanner: ^1.0.1  
 flutter_qr_reader: ^1.0.3  
 qr_flutter: ^3.2.0  
 simple_permissions: 0.1.9  
 flutter_rating_bar: ^3.0.1+1  
 flutter_bloc: ^6.0.1  
 flutter_slidable: ^0.5.5  
 flutter_screenutil: ^2.3.1  
 number_display: ^2.3.0  
 flutter_svg: ^0.18.0  
 flutter_swiper: ^1.1.6  
 amap_location_fluttify: ^0.13.2  
 decorated_flutter: ^0.18.0  
 amap_map_fluttify: ^0.24.0+3  
 amap_location_fluttify

- 使用这个组件的时候，需要同时集成 amap_all_fluttify
  amap_all_fluttify: ^0.17.0
  包含搜索, 定位, 地图, 简单整合了 amap_search_fluttify,amap_location_fluttify,amap_map_fluttify. 从 0.16.0 开始, 添加了一些组合了定位, 地图, 搜索的一些功能:

demo_widgets: ^0.2.0

获取经纬度  
 geolocator: ^5.3.2+2  
 latlong: ^0.6.1

- Lightweight library for common latitude and longitude calculation

flutter_staggered_grid_view: ^0.3.1  
 flutter_staggered_animations: ^0.1.2  
 carousel_slider: ^2.2.1  
 auto_size_text: ^2.1.0  
 get_it: ^4.0.4  
 styled_widget: ^0.2.1+2

- Simplifying your widget tree structure by defining widgets using methods.
  shimmer: ^1.1.1
- A package provides an easy way to add shimmer effect in Flutter project 闪烁；发闪烁的微光

file_picker: ^1.13.3

动画  
 simple_animations: ^2.2.1  
 lottie: ^0.5.1  
 flutter_villains: ^1.2.1  
 flare_flutter: ^2.0.5  
 animations: ^1.1.2  
 animator: ^2.0.1

video_thumbnail: ^0.2.2 视频缩略  
 flutter_cache_manager: ^1.4.1  
 image: ^2.1.14

- A Dart library providing the ability to load, save and manipulate images in a variety of different file formats.
  Load a jpeg, resize it, and save it as a png
  Create an image, draw some text, save it as a png

localstorage: ^3.0.2+5  
 open_file: ^3.0.1

- A plug-in that can call native APP to open files with string result in flutter,support iOS(UTI) and android(intent)
  一个插件，可以调用本地应用程序打开文件与字符串结果扑，支持 iOS(UTI)和 android(意图)

network_to_file_image: ^2.3.1  
 flutter_mobx: ^1.1.0+1

android_intent: ^0.3.7+2  
 android_alarm_manager: ^0.4.5+11

- A Flutter plugin for accessing the Android AlarmManager service, and running Dart code in the background when alarms fire.
  android 定时服务

sqflite: ^1.3.1  
 rxdart: ^0.24.1

- RxDart adds additional capabilities to Dart Streams and StreamControllers.
  Rx.concat([
  Stream.value(1),
  Rx.timer(2, Duration(days: 1)),
  Stream.value(3)
  ])
  .listen(print); // prints 1, 2, 3

flutter_full_pdf_viewer: 1.0.6  
 pdf: ^1.9.0

- To load an image from a file:
  To save the pdf file:

cached_network_image: ^2.0.0  
 flutter_blurhash: ^0.5.0

- Compact representation of a placeholder for an image. 图像占位符的紧凑表示。  
  SizedBox.expand(  
   child: Center(  
   child: AspectRatio(  
   aspectRatio: 1.6,  
   child: BlurHash(hash: "L5H2EC=PM+yV0g-mq.wG9c010J}I"),  
   ),  
   ),  
  ),

google_fonts: ^1.0.0  
 image_cropper: ^1.2.3  
 image_editor: ^0.7.1

- 图片功能很多
  Option  
  Flip  
  Clip  
  Rotate  
  Color Martix  
  Scale  
  AddText  
  FontManager  
  MixImage  
  BlendMode

giffy_dialog: ^1.8.0  
 search_widget: ^1.0.2  
 avatar_glow: ^1.2.0  
 font_awesome_flutter: ^8.8.1

- The Font Awesome Icon pack available as set of Flutter Icons.
  Regular
  Solid
  Brands

flutter_json_widget: ^1.0.2

- 展示 json 数据，点击可以展开，树形结构

json_table: ^1.4.0

- 根据 json 数据展示 table

dynamic_widget: ^2.0.2

- 根据 json 数据展示界面，涉及 json 数据解析

simple_animations: ^2.2.1

- Simple Animations is a powerful framework to create beautiful custom animations in no time.

modal_bottom_sheet: ^0.2.0+1

- Create awesome and powerful modal bottom sheets.

bezier_chart: ^1.0.17+1

- A beautiful bezier line chart widget for flutter that is highly interactive and configurable.

bezier: ^1.1.5  
 vector_math: ^2.0.8  
 loading_animations: ^2.1.0  
 intro_slider: ^2.3.1  
 photo_view: ^0.9.2

引入的插件太多
extended_image: ^1.1.0

- Official extension image, support placeholder(loading)/ failed state, cache network, zoom/pan, photo view, slide out page, editor(crop,rotate,flip), painting etc.
  官方扩展图片，支持占位符(加载)/失败状态，缓存网络，缩放/平移，照片视图，滑出页面，编辑器(裁剪，旋转，翻转)，绘画等。

loading_more_list: ^3.0.0  
extended_text: 3.0.1  
image_editor: ^0.1.2  

table_calendar: ^2.2.3  
- Highly customizable, feature-packed Flutter Calendar with gestures, animations and multiple formats.
Customizable Icons for Flutter，you can use with over 3K+ icons in your flutter project

flutter_icons: ^1.1.0  
material_design_icons_flutter: ^4.0.5345  
sensors: 0.4.2+2  
progress_dialog: ^1.2.4  
smooth_page_indicator: ^0.2.0  

flutter_easyrefresh: ^2.1.5  
- A flutter widget that provides pull-down refresh and pull-up load.

flutter_spinkit: ^4.1.2+1  
dots_indicator: ^1.2.0  
states_rebuilder: ^2.3.1  
velocity_x: ^0.4.1  
flushbar: ^1.10.4  
responsive_builder: ^0.2.0+2  
printing: ^3.5.0  
pdf: ^1.6.0  
introduction_screen: ^1.0.9  
dotted_border: ^1.0.6  
awesome_dialog: ^1.1.3  
flutter_downloader: ^1.4.4  
audioplayers: ^0.15.1  
just_audio: ^0.2.2  
sliding_sheet: ^0.3.7  
grouped_list: ^3.3.0  
convex_bottom_bar: 2.4.0
- 底部导航 tabbar A Flutter package which implements a ConvexAppBar to show a convex tab in the bottom bar. Theming supported.
报错，暂时还不能使用

flappy_search_bar: ^1.7.2  
expandable_bottom_bar: ^1.0.2  
bottom_navy_bar: ^5.5.0  
bubble_bottom_bar: ^1.2.0  
spincircle_bottom_bar: ^1.0.0  
scroll_bottom_navigation_bar: ^3.0.0  
animated_bottom_navigation_bar: ^0.1.2+2  
persistent_bottom_nav_bar: ^2.0.5  

scrollable_positioned_list: ^0.1.7

pull_to_refresh: ^1.6.1  
flutter_staggered_grid_view: ^0.3.0  
flutter_spinkit: 2.1.0  
residemenu: 1.3.7  
fish_redux: ^0.2.2  
shimmer: 1.0.0  
flutter_sticky_header: ^0.4.5  
flutter_gifimage: ^1.0.0  
flutter_swiper: ^1.1.6  

full_screen_menu: ^0.1.2  
flutter_inappwebview: ^4.0.0+4  
hidden_drawer_menu: ^2.0.1  
status_alert: any  
settings_ui: ^0.3.0  
device_preview: 0.3.0+1  
flutter_easyloading: ^1.1.4  
loading_animations: ^2.1.0  
flutter_custom_dialog: ^1.0.20  
responsive_framework: 0.0.7 
- Easily make Flutter apps responsive. Automatically adapt UI to different screen sizes. Responsiveness made simple.

web_socket_channel: ^1.1.0  

keyboard_avoider: ^0.1.2  

toast: ^0.1.5    
bot_toast: ^3.0.1   

frefresh: ^1.1.0  
fsuper: ^0.1.5  
fradio: ^1.0.1  
ffloat: ^1.0.0  
fswitch: ^1.1.2  
fbutton: ^1.0.4  

palette_generator: ^0.2.3  
launch_review: ^2.0.0  
- A Flutter plugin to assist in leaving user reviews/ratings in Google Play Store and Apple App Store.

package_info: ^0.4.1  
scroll_to_index: ^1.0.6  
badges: ^1.1.1  
flutter_app_badger: ^1.1.2  

azlistview: ^0.1.2  
lpinyin: ^1.0.7  

city_pickers: ^0.1.30  
flutter_colorpicker: ^0.2.2  

dragablegridview_flutter: ^0.2.5  

transparent_image: ^1.0.0  
- A transparent image in Dart code, represented as a Uint8List.
透明图像，表示为 Uint8List。
透明图片控件 Uint8List

tobias: ^1.7.1+1  
- 集成这个插件之后，重新停止运行项目，应用会闪退
Tobias 是一个为支付宝支付 SDK 做的 Flutter 插件。

fluwx: ^2.3.0  
- 适用于 Flutter 的微信 SDK

share: ^0.6.4+3  

flutter_local_notifications: ^1.4.4+3  
http: ^0.12.0+4  
path_provider: ^1.6.1  
shared_preferences: ^0.5.6+2  
rxdart: ^0.23.1  
rxdart: ^0.24.1  

parallax_image: ^0.3.1+1  
fluro: ^1.6.3  
- Fluro is a Flutter routing library that adds flexible routing options like wildcards, named parameters and clear route definitions.
Fluro 是一个颤振路由库，它添加了灵活的路由选项，如通配符、命名参数和清晰的路由定义。

chewie: ^0.9.10  
flutter_image_compress: ^0.7.0  
- compress image with native code(objc kotlin), it's faster. This library can work on android/ios.

cool_ui: ^0.6.3  
- Some practical Widget for flutter,Popover,Weui,Custom Keyboard
自定义键盘

spritewidget: ^0.9.24  
- SpriteWidget is an open source toolkit for building complex, high performance animations and 2D games with Flutter.

rx_command: 5.0.3   
rx_widgets: ^3.0.0  

stacked: 1.7.6  

flutter_hooks: ^0.13.1  
flutter_statusbarcolor: ^0.2.3  
flutter_statusbar_manager: ^1.0.2  
multi_image_picker: ^4.7.11  

sky24n
common_utils: ^1.2.1  
flustars: ^0.3.3 
- Flutter common utils library. SpUtil, ScreenUtil, WidgetUtil, DirectoryUtil, ImageUtil. SharedPreferences Util. Screen info & Screen adaptation. get image size.

flutter_boost: ^1.12.13+3  
overlay_support: ^1.0.5  
gallery_saver: ^2.0.1  
image_gallery_saver: ^1.5.0  
flutter_xupdate: ^0.0.4  

mobx: ^1.1.1  
flutter_mobx: ^1.1.0  

flutter_masked_text: ^0.8.0 
- 掩蔽文本

openflutter
gesture_password: ^0.0.6
ok_image: ^0.4.0  
page_indicator: ^0.3.0  
flutter_page_indicator: ^0.0.3  
nautilus: ^0.0.7 
- Nautilus 是阿里百川电商 SDK 在 Flutter 上的实现，通过 Nautilus 可以实现淘宝登录，打开淘宝商品详情等功能。

loadmore: ^1.0.4  
neeko: ^0.0.10 
- Simple video player widget based on video_player, inspired by youtube_player_flutter. Neeko supports more actions such as timeline control, screen orientation control and so on.

flutter_paging: ^0.0.5  
paging: ^0.1.0  
rating_bar: ^0.2.0  
mini_calendar: ^0.3.2  
pangolin: ^0.2.3  
-  Flutter 广告 SDK-字节跳动-穿山甲 集成

mmkv_flutter: ^1.0.10 
- penflutter Get or set persistent storage value base on MMKV framework.

flutter_mmkv: ^1.0.0  
dropdown_menu: ^1.1.1  
linker: ^0.0.2  
flutter_wechat_ble: ^0.1.4 
- A ble library with wechat api style for flutter. 微信 api 风格的蓝牙库 Ble plugin for flutter, android & ios support.

scrolling_page_indicator: ^0.1.3  
lazy_indexed_stack: ^0.0.1  
transformer_page_view: ^0.1.6  

curved_navigation_bar: ^0.3.3  
device_info: ^0.4.2+7  
marquee: ^1.5.3  
searchable_dropdown: ^1.1.3  
flutter_dropdown: ^0.0.8  
dropdown_banner: ^1.4.0  
dropdown_search: ^0.4.4  
gzx_dropdown_menu: ^2.1.0 
- A custom is strong dropdown menu for Flutter. Easy to use and powerful for customization, it's up to you what you want to display in the dropdown menu!

syncfusion_flutter_calendar: ^18.2.55  
syncfusion_flutter_core: ^18.2.55 
- Syncfusion Flutter Core is a dependent package for all the Syncfusion Flutter widgets.

horizontal_calendar_widget: ^1.0.2  
syncfusion_flutter_sliders: ^18.2.55-beta  
syncfusion_flutter_datepicker: ^18.2.55-beta  

fluttercandies
wechat_assets_picker: ^4.2.1  
flutter_custom_calendar: ^1.0.4+0.5  
extended_text_field: ^4.0.0  
wechat_camera_picker: ^1.2.0  
backdrop: ^0.4.3  
flutter_calendar_carousel: ^1.4.12  

photo_manager: ^0.5.8 
- You can scan photos and albums. Only api, not have ui. you can use the api to create your image picker. or use photo

loading_more_list: ^3.0.1  
extended_nested_scroll_view: ^1.0.1 
- extended nested scroll view to fix pinned header and inner scrollables sync issues.
扩展嵌套滚动视图，以修复固定头和内部滚动同步问题。

like_button: ^1.0.1  
ff_annotation_route: 1.0.8 ^3.4.0  

flutter_audio_recorder: ^0.5.5  
file: ^5.0.4  
audioplayers: ^0.13.2  

expandable: ^4.1.4  
flutter_speed_dial: ^1.2.5  
flare_splash_screen: ^3.0.1  
flutter_native_splash: ^0.1.9  

animated_splash: ^1.0.0  
animated_splash_screen: ^1.0.0+1  
flutter_splash_screen: ^0.1.0  
flame_splash_screen: ^0.0.1  
fancy_bottom_navigation: ^0.3.2  
flutter_unity_widget: ^0.1.6+8 
- 集成报错，项目内部 build 失败

flutter_platform_widgets: ^0.60.2 0.32.5  
liquid_pull_to_refresh: ^2.0.0  
liquid_swipe: ^1.5.0  
animated_text_kit: ^2.2.0  
flutter_tags: ^0.4.8+2  
flutter_android: ^0.8.0  
- Activity launch android_content.Intent#startActivity()
Bluetooth scanning android_bluetooth.BluetoothLeScanner
Distance calculation android_location.Location.distanceBetween()
Face detection android_media.FaceDetector
Heart-rate monitoring android_hardware.SensorManager.getDefaultSensor()
Parcel serialization android_os.Parcel
Sensor event streams android_hardware.Sensor#subscribe()

flutter_fluid_slider: ^1.0.3  
snaplist: ^0.1.8  
infinite_listview: ^1.0.1+1  
-  ListView with items that can be scrolled infinitely in both directions.

passcode_screen: ^1.2.0  
progress_button: ^0.0.2  
progress_state_button: ^1.0.1  
modal_progress_hud: ^0.1.3  
liquid_progress_indicator: ^0.3.2  
step_progress_indicator: ^0.2.4+7  
intro_views_flutter: ^2.8.1  
flutter_blue: 0.7.1+1 ^0.7.2  
flutter_blue: ^0.7.2  
mxflutter: ^0.2.5  
flutter_bugly: ^0.2.8  

injectable: ^1.0.4  
flutter_modular: ^1.3.2  
get: ^3.4.2  
get: ^3.5.1  
get_it: ^4.0.4  

plugins no 界面
event_bus: ^1.1.1  
uuid: ^2.2.0  
tuple: ^1.0.3  
sprintf: ^4.0.0  
strings: ^0.1.2  
equatable: ^1.2.3  
string_validator: ^0.1.4  
dartz: ^0.9.1  
dartx: ^0.5.0  
crypto: 2.1.4 加密相关

useless
visibility_detector: ^0.1.5  
- A widget that detects the visibility of its child and notifies a callback.

country_code_picker: ^1.4.0  

easy_localization: ^2.3.2  

carousel_pro:  
&nbsp; git:  
&nbsp;&nbsp; url: git://github.com/jlouage/flutter-carousel-pro.git   
&nbsp;&nbsp;&nbsp; ref: master  
