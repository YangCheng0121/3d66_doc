# 默认皮肤详解

```xml
<!-- krpano 1.19.pr8 - Virtual Tour Skin -->
<!-- maps="false"  是否使用必应地图或谷歌地图
maps_type="bing"  选择使用谷歌地图或必应地图
maps_bing_api_key=""   必应地图所需的API密钥，需申请
maps_google_api_key=""   谷歌地图所需的API密钥，需申请
maps_zoombuttons="false"   是否在地图上显示缩放按钮
gyro="true"   是否使用陀螺仪
webvr="true"    是否启用VR
webvr_gyro_keeplookingdirection="false" 进入陀螺仪或VR时是否保持观看方向
webvr_prev_next_hotspots="true"  在VR下是否启用导航到前后场景的链接热点
littleplanetintro="false"    是否使用小行星开场
title="true"  是否左下角显示title
thumbs="true"  是否使用缩略图，如不使用，则没有缩略图一栏
thumbs_width="120" thumbs_height="80" thumbs_padding="10" thumbs_crop="0|40|240|160"  缩略图宽度、高度、间距以及缩略图裁切范围
thumbs_opened="false"   是否在启动时弹出缩略图一栏
thumbs_text="false"  是否在缩略图上显示名字
thumbs_dragging="true"   是否允许鼠标拖拽缩略图区域
thumbs_onhoverscrolling="false"  是否允许鼠标悬停缩略图自动滚动
thumbs_scrollbuttons="false"   是否显示缩略图滚动按钮
thumbs_scrollindicator="false"   是否显示缩略图滚动条
thumbs_loop="false"  滚动按钮是否使用缩略图循环
tooltips_buttons="false" 鼠标在按钮悬停时是否弹出文字提示
tooltips_thumbs="false"  鼠标在缩略图悬停时是否弹出文字提示
tooltips_hotspots="false"   鼠标在热点上悬停时是否弹出文字提示
tooltips_mapspots="false"   鼠标在地图热点悬停时是否弹出文字提示
deeplinking="false"       是否使用深度链接获取功能，可使得当前页面路径获取场景及视角信息
loadscene_flags="MERGE"  缩略图切换场景时的变量
loadscene_blend="OPENBLEND(0.5, 0.0, 0.75, 0.05, linear)"  缩略图切换场景时的融合
loadscene_blend_prev="SLIDEBLEND(0.5, 180, 0.75, linear)"  缩略图切换到上一个场景时的融合
loadscene_blend_next="SLIDEBLEND(0.5, 0, 0.75, linear)"  缩略图切换到下一个场景时的融合
loadingtext="载入中..." 在全景图载入中时显示的文字
layout_width="100%"  导航条容器相对屏幕宽度的百分比
layout_maxwidth="814"  导航条容器的最大宽度像素
controlbar_width="-24" 导航条背景的宽度像素
controlbar_height="40"  导航条背景的高度像素
controlbar_offset.normal="20"  导航条背景与屏幕底部的距离
controlbar_offset_closed="-40"  导航条隐藏状态时与屏幕底部的距离
controlbar_overlap.no-fractionalscaling="10"  在不支持分级缩放页面和设置像素比的设备的导航条重叠的像素
controlbar_overlap.fractionalscaling="0" 支持分级缩放页面和设置像素比的设备的导航条重叠的像素
design_skin_images="vtourskin.png" 皮肤所用的源图片
design_bgcolor="0x000000" 皮肤的背景颜色
design_bgalpha="0.5" 皮肤的透明度
design_bgborder="0 0xFFFFFF 1.0" 皮肤的边框
design_bgroundedge="1" 皮肤边框圆角设置
design_bgshadow="0 0 9 0xFFFFFF 0.5" 皮肤的背景阴影
design_thumbborder_bgborder="4 0xFFFFFF 1.0" 皮肤的缩略图边框
design_thumbborder_padding="2" 皮肤缩略图边框间距
design_thumbborder_bgroundedge="5" 皮肤缩略图边框的圆角
design_text_css="color:#FFFFFF; font-family:Arial; font-weight:bold;"皮肤文字样式
design_text_shadow="1" 皮肤的文字阴影 -->
<skin_settings maps="false" 
               maps_type="google"
               maps_bing_api_key=""
               maps_google_api_key=""
               maps_zoombuttons="false"
               gyro="true"
               webvr="true"
               webvr_gyro_keeplookingdirection="false"
               webvr_prev_next_hotspots="true"
               littleplanetintro="false"
               title="true"
               thumbs="true"
               thumbs_width="120" thumbs_height="80" thumbs_padding="10" thumbs_crop="0|40|240|160"
               thumbs_opened="false"
               thumbs_text="false"
               thumbs_dragging="true"
               thumbs_onhoverscrolling="false"
               thumbs_scrollbuttons="false"
               thumbs_scrollindicator="false"
               thumbs_loop="false"
               tooltips_buttons="false"
               tooltips_thumbs="true"
               tooltips_hotspots="false"
               tooltips_mapspots="false"
               deeplinking="false"
               loadscene_flags="MERGE"
               loadscene_blend="OPENBLEND(0.5, 0.0, 0.75, 0.05, linear)"
               loadscene_blend_prev="SLIDEBLEND(0.5, 180, 0.75, linear)"
               loadscene_blend_next="SLIDEBLEND(0.5,   0, 0.75, linear)"
               loadingtext="loading..."
               layout_width="100%"
               layout_maxwidth="814"
               controlbar_width="-24"
               controlbar_height="40"
               controlbar_offset="20"
               controlbar_offset_closed="-40"
               controlbar_overlap.no-fractionalscaling="10"
               controlbar_overlap.fractionalscaling="0"
               design_skin_images="vtourskin.png"
               design_bgcolor="0x2D3E50"
               design_bgalpha="0.8"
               design_bgborder="0"
               design_bgroundedge="1"
               design_bgshadow="0 4 10 0x000000 0.3"
               design_thumbborder_bgborder="3 0xFFFFFF 1.0"
               design_thumbborder_padding="2"
               design_thumbborder_bgroundedge="0"
               design_text_css="color:#FFFFFF; font-family:Arial;"
               design_text_shadow="1"
               />
 
 
<!-- save the url path of this xml file (the url value will be adjusted during xml parsing) -->
<vtourskinxmlpath url="./" />
 
 
<!-- mouse / touch / keyboard(button) control settings - http://krpano.com/docu/xml/#control -->
<!-- 鼠标触屏键盘控制的设定 -->
<control mouse="drag"
         touch="drag"
         zoomtocursor="false"
         zoomoutcursor="false"
         draginertia="0.1"
         dragfriction="0.9"
         movetoaccelerate="1.0"
         movetospeed="10.0"
         movetofriction="0.8"
         keybaccelerate="0.09"
         keybfriction="0.94"
         keybfovchange="0.25"
         mousefovchange="1.0"
         fovspeed="3.0"
         fovfriction="0.9"
         bouncinglimits="true"
         />
 
<!-- mouse cursors - http://krpano.com/docu/xml/#cursors -->
<!-- 鼠标光标设定可自定义光标的样式 -->
<cursors standard="default"
         dragging="move"
         moving="move"
         />
 
 
<!-- ensure stagescale 2x for mobile devices (regardless if mobilescale is 0.5 or 1.0) -->
 
<krpano stagescale="calc:stagescale * 2" if="stagescale LT 1.0" devices="mobile" />
 
 
<!-- include VR support - http://krpano.com/plugins/webvr/ -->
<!-- WebVR插件 -->
<include url="%SWFPATH%/plugins/webvr.xml" devices="html5" />
 
<!-- overwrite some settings from the webvr.xml for the skin integration -->
<!-- 覆盖WebVR默认设定 -->
<!-- onavailable去除插件自定义的进入VR按钮（因为皮肤中已包含）webvr_enterbutton 
skin_arrange_buttons初始化皮肤按钮  webvr_onavailable()初始化设定，显示Enter VR 按钮-->
<!-- onentervr skin_showloading去除加载文字 webvr_setup 设置场景切换热点并跟随
webvr_onentervr 将所有没有添加vr="true"的layer隐藏，并显示VR的Layer skin_reloadscene_webvr
显示屏幕旋转提示图片-->
<plugin name="WebVR" keep="true" devices="html5"
        pluginurl="%SWFPATH%/plugins/webvr.js"
        url=""
        multireslock.desktop="true"
        multireslock.mobile.or.tablet="false"
        mobilevr_support="true"
        mobilevr_fake_support="true"
        onavailable="removelayer(webvr_enterbutton); skin_arrange_buttons(); webvr_onavailable();"
        onentervr="skin_showloading(false); webvr_onentervr(); webvr_setup(); skin_reloadscene_webvr();"
        onexitvr="webvr_onexitvr(); webvr_setup(); skin_reloadscene_webvr();"
        />
 
<!-- webvr button style (adjust to match skin style) -->
<!-- 修改WebVR界面的style使其符合当前场景的样式 主要设置背景颜色和文字 -->
<style name="webvr_button_style"
       border="false"
       roundedge="calc:1.0"
       backgroundcolor="get:skin_settings.design_bgcolor" backgroundalpha="get:skin_settings.design_bgalpha"
       shadow="0.01" shadowrange="10.0" shadowangle="90.0" shadowcolor="0x30261B" shadowalpha="0.50"
       css="calc:skin_settings.design_text_css + ' color:#FFFFFF;font-size:' + 20*webvr_setup_scale*webvr_button_scale + 'px;'"/>
 
<!-- show a 'rotate the device' info when the mobile device is in portrait orientation in VR mode -->
<!-- 显示屏幕旋转提示图片 devices="mobile" 只在手机模式下-->
<layer name="webvr_rotate_to_landscape_request" keep="true" vr="true" devices="mobile"
       url="rotate_device.png" scale="0.5"
       align="top" edge="center" y="28%"
       autoalpha="true" alpha="0.0"
       enabled="false"
       />
<!-- WebVR相关事件触发 webvr_set_startup_view 设置镜头位置 onloadcomplete根据场景数目觉得是否显示VR场景切换热点-->
<events name="webvr_events" keep="true" devices="html5"
        onxmlcomplete="webvr_set_startup_view()"
        onresize.mobile="webvr_act_as_gyro_in_portrait_mode();"
        onloadcomplete="delayedcall(0.5, if(webvr.isenabled AND scene.count GT 1 AND skin_settings.webvr_prev_next_hotspots, set(hotspot[webvr_prev_scene].visible,true); set(hotspot[webvr_next_scene].visible,true); ); );"
        onviewchange=""
        />
<!-- 根据VR是否打开设置镜头位置 -->
<action name="webvr_set_startup_view">
    if((webvr.isenabled OR plugin[skin_gyro].enabled) AND skin_settings.webvr_gyro_keeplookingdirection == false,
        skin_lookat( get(xml.view.hlookat) );
      );
</action>
 
<!-- 进入VR时设定 -->
<action name="webvr_setup">
    if(webvr.isenabled,
        <!-- 读取自定义设定 -->
        copy(loadscene_flags_backup, skin_settings.loadscene_flags);
        <!-- 设置为 MERGE|KEEPVIEW|KEEPMOVING|NOPREVIEW-->
        set(skin_settings.loadscene_flags, MERGE|KEEPVIEW|KEEPMOVING|NOPREVIEW);
        <!-- 打开WebVR时是否竖屏启动陀螺仪 -->
        webvr_act_as_gyro_in_portrait_mode(true);
        <!-- 读取设置是否显示VR模式下的上下按钮 并且设置跟随-->
        if(scene.count GT 1 AND skin_settings.webvr_prev_next_hotspots,
            set(hotspot[webvr_prev_scene].visible, true);
            set(hotspot[webvr_next_scene].visible, true);
            set(events[webvr_events].onviewchange, webvr_menu_following());
          );
      ,
        if(loadscene_flags_backup !== null, copy(skin_settings.loadscene_flags, loadscene_flags_backup));
        tween(layer[webvr_rotate_to_landscape_request].alpha, 0.0, 0.0);
        set(hotspot[webvr_prev_scene].visible, false);
        set(hotspot[webvr_next_scene].visible, false);
        set(events[webvr_events].onviewchange, null);
      );
</action>
<!-- 打开WebVR时是否竖屏启动陀螺仪 -->
<action name="webvr_act_as_gyro_in_portrait_mode">
    if(device.mobile AND webvr.isenabled,
        div(aspect, stagewidth, stageheight);
        if(aspect != lastaspect OR '%1' == 'true',
            copy(lastaspect, aspect);
            if(stagewidth GT stageheight,
                <!-- landscape orientation - use stereo rendering and a direct/fast gyro sensor mode -->
                set(display.stereo, true);
                set(webvr.mobilevr_sensor_mode, 3);
                webvr.update();
                tween(layer[webvr_rotate_to_landscape_request].alpha, 0.0, 0.0);
              ,
                <!-- portrait orientation - use normal rendering and a smoother/slower gyro sensor mode -->
                set(display.stereo, false);
                set(webvr.mobilevr_sensor_mode, 1);
                webvr.update();
                tween(layer[webvr_rotate_to_landscape_request].alpha, 1.0);
                delayedcall(3.0, tween(layer[webvr_rotate_to_landscape_request].alpha, 0.0, 1.0); );
              );
          );
      ,
        set(lastaspect, 0);
      );
</action>
 
<!-- VR scene switching hotspots -->
<!-- VR场景切换热点 distorted="true" 热点跟随场景扭曲-->
<style name="webvr_menu_style" depth="800" scale="0.5" distorted="true" ath="0" atv="45" alpha="0.5" />
<hotspot name="webvr_prev_scene" keep="true" style="skin_base|webvr_menu_style" crop="0|64|64|64"  ox="-64" onover="tween(scale,0.6);" onout="tween(scale,0.5);" vr_timeout="750" onclick="skin_nextscene_loop(-1);" visible="false" devices="html5.and.webgl" />
<hotspot name="webvr_next_scene" keep="true" style="skin_base|webvr_menu_style" crop="64|64|64|64" ox="+64" onover="tween(scale,0.6);" onout="tween(scale,0.5);" vr_timeout="750" onclick="skin_nextscene_loop(+1);" visible="false" devices="html5.and.webgl" />
 
<!-- floating/following VR hotspots -->
<!-- 设置VR模式下跟随镜头的场景切换热点 -->
<action name="webvr_menu_following" type="Javascript" devices="html5"><![CDATA[        var hs1 = krpano.get("hotspot[webvr_prev_scene]");
    var hs2 = krpano.get("hotspot[webvr_next_scene]");
    //头追没有移动到热点处的时候
    if(!hs1.hovering && !hs2.hovering)
    {
        var f = 0.01;   // following speed factor
        var h = krpano.view.hlookat;//获取当前场景的垂直度数（垂直180°）
        var v = krpano.view.vlookat;//获取当前场景的水平度数（水平360°）
        var hsh = hs1.ath;
        var hsv = hs1.atv;
        //将度数转化为距离设置到热点上
        h   = (h  -(h|0))   + (((h|0)  +360180)%360) - 180.0;
        v   = (v  -(v|0))   + (((v|0)  +360180)%360) - 180.0;
        hsh = (hsh-(hsh|0)) + (((hsh|0)+360180)%360) - 180.0;
        var dh = h - hsh;
        dh += (dh > 180) ? -360 : (dh < -180) ? 360 : 0
        hsh += dh*f;
        var a = Math.abs(v - hsv) / 90.0;
        a = 1.0 * Math.max(1.0 - 2.0*Math.sqrt(a), 0);
        v = v + 55.0 - v*1.5;
        hsv = hsv*(1.0 - f) + v*f;
        hs1.ath = hs2.ath = hsh;
        hs1.atv = hs2.atv = hsv;
        hs1.alpha = hs2.alpha = a;
    }
]]></action>
<!-- VR support -->
 
 
 
<!-- skin styles -->
 
<!-- skin_base - the base skin image -->
<!-- 基础样式，设置皮肤的图标文件路径 -->
<style name="skin_base" url="calc:vtourskinxmlpath.url + skin_settings.design_skin_images" />
 
 
<!-- skin_glow - button glowing (if additional ondown,onup,onout,over events are needed, this style provides ondown2,onup2,onover2,onout2 events) -->
<!-- 样式属性，如果有额外的事件监听使用 ondown2,onup2,onover2,onout2 skin_buttonglow 设置按钮的点击hover效果-->
<style name="skin_glow"
       ondown="copy(skin_lockglow,name); skin_buttonglow(get(name)); if(ondown2, ondown2() );"
       onover="if(skin_lockglow === null, copy(skin_lockglow,name); skin_buttonglow(get(name),0.3) ); if(onover2, onover2() );"
       onout="if(skin_lockglow === name AND !pressed, skin_buttonglow(null);delete(skin_lockglow); ); if(onout2, onout2() );"
       onup="if(onup2, onup2()); delayedcall(0, if(hovering AND enabled, skin_buttonglow(get(name),0.3); , skin_buttonglow(null);delete(skin_lockglow); ); );"
       />
 
<!-- skin_thumbtext_style - style/textfield for the (optional, skin_settings.thumbs_text) thumbnails texts -->
<!-- 场景缩略图的文字样式 通过skin_settings.thumbs_text设定是否显示缩略图的文字-->
<style name="skin_thumbtext_style" url="%SWFPATH%/plugins/textfield.swf" align="bottom" width="100%" autoheight="true" y="5" enabled="false" background="false" border="false" css="calc:skin_settings.design_text_css + ' text-align:center; font-size:10px;'" textshadow="get:skin_settings.design_text_shadow" />
 
<!-- skin_hotspotstyle - style for the hotspots -->
<!-- 当前皮肤热点的按钮样式 如果skin_settings.tooltips_hotspots为true 则将scene的title属性值设置为热点的tips-->
<style name="skin_hotspotstyle" url="vtourskin_hotspot.png" scale="0.5" edge="top" distorted="true"
       tooltip=""
       linkedscene=""
       linkedscene_lookat=""
       onclick="skin_hotspotstyle_click();"
       onover="tween(scale,0.55);"
       onout="tween(scale,0.5);"
       onloaded="if(linkedscene AND skin_settings.tooltips_hotspots, copy(tooltip,scene[get(linkedscene)].title); loadstyle(skin_tooltips); );"
       />
<!-- 热点点击 读取热点的linkedscene属性设置为跳转的scene如果存在linkedscene_lookat属性则按照","切分字符分别赋值给h,v,fov
点击时隐藏tips 调用skin_loadscene打开场景skin_lookat旋转到指定位置-->
<action name="skin_hotspotstyle_click">
    if(linkedscene,
        if(linkedscene_lookat,
            txtsplit(linkedscene_lookat, ',', hs_lookat_h, hs_lookat_v, hs_lookat_fov);
          );
        set(enabled, false);
        skin_hidetooltips();
        tween(depth|alpha|oy|rx, 4000|0.0|-50|-60, 0.5, default,
            skin_loadscene(get(linkedscene), get(skin_settings.loadscene_blend));
            if(hs_lookat_h !== null,
                skin_lookat(get(hs_lookat_h), get(hs_lookat_v), get(hs_lookat_fov));
                delete(hs_lookat_h, hs_lookat_v, hs_lookat_fov);
              );
            skin_updatescroll();
          );
      );
</action>
 
 
<!-- skin_tooltip - style for the thumb, hotspot and mapspot tooltips -->
<!-- tips样式，当前为鼠标移动到layer读取tooltip值设置到mouse.stagex  mouse.stagey（为鼠标的topleft位置） 这个位置-->
<style name="skin_tooltips"
       onover.mouse="copy(layer[skin_tooltip].html, tooltip);
                     set(layer[skin_tooltip].visible, true);
                     tween(layer[skin_tooltip].alpha, 1.0, 0.1);
                     asyncloop(hovering, copy(layer[skin_tooltip].x,mouse.stagex); copy(layer[skin_tooltip].y,mouse.stagey); );"
       onout.mouse="tween(layer[skin_tooltip].alpha, 0.0, 0.1, default, set(layer[skin_tooltip].visible,false), copy(layer[skin_tooltip].x,mouse.stagex); copy(layer[skin_tooltip].y,mouse.stagey); );"
       />
 
 
<!-- the tooltip textfield -->
<!-- 文字提示tips layer使用文字插件展示，这里可以修改tips的式样 -->
<layer name="skin_tooltip" keep="true"
       url="%SWFPATH%/plugins/textfield.swf"
       parent="STAGE"
       visible="false" alpha="0" enabled="false" zorder="2"
       align="lefttop" edge="bottom" oy="-2" width="200" autoheight="true"
       background="false" backgroundcolor="0xFFFFFF" backgroundalpha="1.0"
       border="false" bordercolor="0x000000" borderalpha="1.0" borderwidth="1.0" roundedge="0"
       shadow="0.0" shadowrange="4.0" shadowangle="45" shadowcolor="0x000000" shadowalpha="1.0"
       textshadow="get:skin_settings.design_text_shadow" textshadowrange="6.0" textshadowangle="90" textshadowcolor="0x000000" textshadowalpha="1.0"
       css="calc:skin_settings.design_text_css + ' text-align:center; font-size:16px;'"
       html=""
       />
 
 
<!-- skin layout -->
<!-- 下方控制条 -->
<layer name="skin_layer" keep="true" type="container" align="top" width="get:skin_settings.layout_width" maxwidth="get:skin_settings.layout_maxwidth" height="100%" maskchildren="true" visible="false" bgcapture="false" zorder="1">
    <!-- 控制条上部分包括视频控制条，缩略图展示，场景名称等 -->
    <layer name="skin_scroll_window" type="container" align="bottom" width="100%" height="100%" x="0" y="calc:skin_settings.controlbar_offset + skin_settings.controlbar_height - skin_settings.controlbar_overlap" maskchildren="true" onloaded="skin_calc_opened_closed();" zorder="1">
        <layer name="skin_scroll_layer" type="container" align="bottom" width="get:skin_settings.controlbar_width" height="100%" x="200" y="200" y_offset="get:skin_settings.controlbar_overlap" accuracy="1" bgalpha="get:skin_settings.design_bgalpha" bgcolor="get:skin_settings.design_bgcolor" bgborder="get:skin_settings.design_bgborder" bgroundedge="get:skin_settings.design_bgroundedge" bgshadow="get:skin_settings.design_bgshadow">
            <!-- 场景名称 -->
            <layer name="skin_title" url="%SWFPATH%/plugins/textfield.swf" align="lefttop" edge="leftbottom" x="4" y="0" zorder="4" enabled="false" background="false" border="false" css="calc:skin_settings.design_text_css + ' text-align:left; font-style:italic; font-size:12px;'" textshadow="get:skin_settings.design_text_shadow" visible="false" onautosized="skin_video_updateseekbarwidth();" />
            <!-- 视频控制条 -->
            <layer name="skin_video_controls" type="container" align="lefttop" edge="leftbottom" width="100%" height="18" visible="false">
                <layer name="skin_video_seekbar_container" type="container" align="lefttop" width="100%" height="100%" bgcapture="true" ondown="skin_video_ondownseeking();" >
                    <layer name="skin_video_seekbar" type="container" bgcolor="0xFFFFFF" bgalpha="0.25" align="center" width="100%" height="2">
                        <layer name="skin_video_loadbar" type="container" bgcolor="0xFFFFFF" bgalpha="0.5" align="left" width="0" height="2" />
                        <layer name="skin_video_seekpos" type="container" bgcolor="0xFFFFFF" bgalpha="1.0" align="left" edge="center" x="0" bgroundedge="8" width="10" height="10" />
                    </layer>
                </layer>
                <layer name="skin_video_time" url="%SWFPATH%/plugins/textfield.swf" align="rightbottom" x="4" enabled="false" background="false" border="false" css="calc:skin_settings.design_text_css + ' text-align:left; font-style:italic; font-size:12px;'" textshadow="get:skin_settings.design_text_shadow" html="0:00 / 0:00" />
            </layer>
            <layer name="skin_scroll_container" type="container" align="lefttop" width="100%" height="100%" x="0" y="0" bgroundedge="get:skin_settings.design_bgroundedge" maskchildren="true">
                <!-- 缩略图展示 -->
                <layer name="skin_thumbs_container" type="container" align="lefttop" width="100%" height="100%" visible="false">
                    <layer name="skin_thumbs_scrollleft"  style="skin_base|skin_glow" crop="0|64|64|64"  align="lefttop"  edge="left"  x="5" y="50" scale="0.5" zorder="2" alpha="1.0" ondown2="asyncloop(pressed, layer[skin_thumbs].scrollby(+2,0));" visible="false" />
                    <layer name="skin_thumbs_scrollright" style="skin_base|skin_glow" crop="64|64|64|64" align="righttop" edge="right" x="5" y="50" scale="0.5" zorder="2" alpha="1.0" ondown2="asyncloop(pressed, layer[skin_thumbs].scrollby(-2,0));" visible="false" />
                    <layer name="skin_thumbs_scrollindicator" type="container" bgcolor="0xFFFFFF" bgalpha="0.25" align="lefttop" width="0" y="100" height="2" visible="false" enabled="false" />
                    <!-- 滑动插件 -->
                    <layer name="skin_thumbs" state="closed" url.flash="%SWFPATH%/plugins/scrollarea.swf" url.html5="%SWFPATH%/plugins/scrollarea.js" direction="h" align="top" width="100%" height="100" zorder="1" onloaded="skin_updatescroll();" onscroll="skin_updatethumbscroll();" />
                </layer>
                <!-- 地图展示 -->
                <layer name="skin_map_container" type="container" align="leftop" width="100%" height="100%" bgroundedge="get:skin_settings.design_bgroundedge" maskchildren="true">
                    <layer name="skin_map" state="closed" url="" visible="false" align="lefttop" width="100%" height="50%" x="0" y="0" zorder="1" lat="0" lng="0" zoom="10" bgalpha="0" maptype="satellite" onmapready="skin_addmapspots();">
                        <maptypecontrol visible="true" align="righttop" x="5" y="5" buttonalign="v" scale.mobile="1.5" />
                        <radar visible="false" headingoffset="0" />
                        <spotstyle name="DEFAULT" url="vtourskin_mapspot.png" activeurl="vtourskin_mapspotactive.png" edge="bottom" x="-5" y="-8" scale="0.5" />
                        <layer name="skin_map_zoom_in"  style="skin_base" visible="get:skin_settings.maps_zoombuttons" crop="9|512|46|64"  align="right" x="0" y="-40" zorder="2" ondown="layer[skin_map].zoomin();  skin_buttonglow(get(name));" onup="skin_buttonglow(null);" />
                        <layer name="skin_map_zoom_out" style="skin_base" visible="get:skin_settings.maps_zoombuttons" crop="73|512|46|64" align="right" x="0" y="+40" zorder="2" ondown="layer[skin_map].zoomout(); skin_buttonglow(get(name));" onup="skin_buttonglow(null);" />
                    </layer>
                </layer>
            </layer>
        </layer>
    </layer>
    <!-- 底部控制条背景图 -->
    <layer name="skin_splitter_bottom" type="container" align="bottom" width="100%" height="calc:skin_settings.controlbar_offset + skin_settings.controlbar_height - skin_settings.controlbar_overlap" y="0" maskchildren="true" onloaded="skin_calc_opened_closed();" zorder="2">
        <layer name="skin_control_bar_bg" type="container" align="bottom" width="get:skin_settings.controlbar_width" height="calc:skin_settings.controlbar_height + skin_settings.controlbar_overlap" x="0" y="get:skin_settings.controlbar_offset" bgcolor="get:skin_settings.design_bgcolor" bgalpha="get:skin_settings.design_bgalpha" bgborder="get:skin_settings.design_bgborder" bgroundedge="get:skin_settings.design_bgroundedge" bgshadow="get:skin_settings.design_bgshadow" />
    </layer>
    <!-- 控制按钮区域 -->
    <layer name="skin_control_bar" type="container" align="bottom" width="get:skin_settings.controlbar_width" height="calc:skin_settings.controlbar_height" x="0" y="get:skin_settings.controlbar_offset" onloaded="skin_calc_opened_closed();" zorder="3">
        <!-- 控制按钮 -->
        <layer name="skin_control_bar_buttons" type="container" align="leftbottom" width="100%" height="get:skin_settings.controlbar_height">
            <!-- 前一个场景按钮 -->
            <layer name="skin_btn_prev"      style="skin_base|skin_glow" crop="0|64|64|64"   align="left"        x="5"    y="0"  scale="0.5" alpha="0.5"  onclick="if(skin_settings.thumbs_loop, skin_nextscene_loop(-1), skin_nextscene(-1) );" />
            <!-- 缩略图按钮，点击后调用skin_showthumbs方法动画展示缩略图-->
            <layer name="skin_btn_thumbs"    style="skin_base|skin_glow" crop="0|128|64|64"  align="left"        x="50"   y="0"  scale="0.5" ondown2="skin_showmap(false); skin_showthumbs();" />
            <!-- 地图按钮，点击后会隐藏缩略图-->
            <layer name="skin_btn_map"       style="skin_base|skin_glow" crop="64|128|64|64" align="left"        x="90"   y="0"  scale="0.5" ondown2="skin_showthumbs(false); skin_showmap();" visible="false" />
            <!-- 导航栏包括上下左右移动放大与缩小，鼠标按下距离+或-1，抬起初始化为默认的0 -->
            <layer name="skin_btn_navi" type="container" align="center" x="0" width="240" height="32">
                <layer name="skin_btn_left"  style="skin_base|skin_glow" crop="0|192|64|64"  align="center"      x="-100" y="0"  scale="0.5" ondown2="set(hlookat_moveforce,-1);" onup2="set(hlookat_moveforce,0);" />
                <layer name="skin_btn_right" style="skin_base|skin_glow" crop="64|192|64|64" align="center"      x="-60"  y="0"  scale="0.5" ondown2="set(hlookat_moveforce,+1);" onup2="set(hlookat_moveforce,0);" />
                <layer name="skin_btn_up"    style="skin_base|skin_glow" crop="0|256|64|64"  align="center"      x="-20"  y="0"  scale="0.5" ondown2="set(vlookat_moveforce,-1);" onup2="set(vlookat_moveforce,0);" />
                <layer name="skin_btn_down"  style="skin_base|skin_glow" crop="64|256|64|64" align="center"      x="+20"  y="0"  scale="0.5" ondown2="set(vlookat_moveforce,+1);" onup2="set(vlookat_moveforce,0);" />
                <layer name="skin_btn_in"    style="skin_base|skin_glow" crop="0|320|64|64"  align="center"      x="+60"  y="0"  scale="0.5" ondown2="set(fov_moveforce,-1);"     onup2="set(fov_moveforce,0);" />
                <layer name="skin_btn_out"   style="skin_base|skin_glow" crop="64|320|64|64" align="center"      x="+100" y="0"  scale="0.5" ondown2="set(fov_moveforce,+1);"     onup2="set(fov_moveforce,0);" />
            </layer>
            <!-- 开启或关闭陀螺仪按钮 -->
            <layer name="skin_btn_gyro"      style="skin_base|skin_glow" crop="0|384|64|64"  align="center"      x="+140" y="0"  scale="0.5" onclick="switch(plugin[skin_gyro].enabled); if(plugin[skin_gyro].enabled, skin_showmap(false));" visible="false" devices="html5" />
            <!-- 进入VR模式按钮 -->
            <layer name="skin_btn_vr"        style="skin_base|skin_glow" crop="0|0|80|64"    align="center"      x="+146" y="0"  scale="0.5" onclick="webvr.enterVR();" visible="false" />
            <!-- 全屏按钮 -->
            <layer name="skin_btn_fs"        style="skin_base|skin_glow" crop="0|576|64|64"  align="right"       x="90"   y="0"  scale="0.5" onclick="switch(fullscreen);" devices="fullscreensupport" />
            <!-- 隐藏控制条按钮 -->
            <layer name="skin_btn_hide"      style="skin_base|skin_glow" crop="0|448|64|64"  align="right"       x="50"   y="0"  scale="0.5" onclick="skin_hideskin()" />
            <!-- 显示控制条按钮 -->
            <layer name="skin_btn_show" type="container" bgcapture="true" align="bottom" width="100%" height="get:skin_settings.controlbar_height" y="calc:skin_settings.controlbar_height - skin_settings.controlbar_offset_closed" onclick="skin_showskin()" onhover="tween(alpha,1.0);" onout="tween(alpha,0.25);" ondown.touch="onhover();" onup.touch="onout();" visible="false" capture="false" alpha="0.0">
                <layer name="skin_btn_show_icon" style="skin_base" crop="64|448|64|64" scale="0.5" align="bottom" y="2" enabled="false" />
            </layer>
            <!-- 下一个场景按钮 -->
            <layer name="skin_btn_next"      style="skin_base|skin_glow" crop="64|64|64|64"  align="right"       x="5"    y="0"   scale="0.5" alpha="0.5"  onclick="if(skin_settings.thumbs_loop, skin_nextscene_loop(+1), skin_nextscene(+1) );" />
            </layer>
        </layer>
    <!-- 显示加载中文字图层 -->
    <layer name="skin_loadingtext" url="%SWFPATH%/plugins/textfield.swf" align="center" x="5" y="-5" html="get:skin_settings.loadingtext" visible="false" autoheight="true" background="false" border="false" enabled="false" css="calc:skin_settings.design_text_css + ' text-align:center; font-style:italic; font-size:22px;'" textshadow="get:skin_settings.design_text_shadow" />
    <!-- 发光的背景图片，用于按钮点击效果 -->
    <layer name="skin_buttonglow"  style="skin_base" crop="64|384|64|64" align="center" x="0" y="1" scale="1.0" alpha="0.0" visible="false" enabled="false" />
    <!-- 缩略图选择边框效果 -->
    <layer name="skin_thumbborder" type="container" x="get:skin_settings.design_thumbborder_padding" y="get:skin_settings.design_thumbborder_padding" width="calc:skin_settings.thumbs_width - 2*skin_settings.design_thumbborder_padding" height="calc:skin_settings.thumbs_height - 2*skin_settings.design_thumbborder_padding" visible="false" enabled="false" align="lefttop" bgborder="get:skin_settings.design_thumbborder_bgborder" bgroundedge="get:skin_settings.design_thumbborder_bgroundedge" />
</layer>
 
<!-- previous/next scene buttons for the hidden skin mode -->
<!-- 隐藏控制条时显示的用于场景切换的按钮 -->
<layer name="skin_btn_prev_fs" keep="true" type="container" align="lefttop"  x="-50" width="40" height="100%" bgcapture="true" alpha="0.25" capture="false" zorder="2" onclick="skin_nextscene_loop(-1);" onhover="tween(alpha,1.0);" onout="tween(alpha,0.25);" ondown.touch="onhover();" onup.touch="onout();">
    <layer name="skin_btn_prev_fs_icon" style="skin_base" crop="0|64|64|64"  align="center" scale="0.5" enabled="false" />
</layer>
<layer name="skin_btn_next_fs" keep="true" type="container" align="righttop" x="-50" width="40" height="100%" bgcapture="true" alpha="0.25" capture="false" zorder="2" onclick="skin_nextscene_loop(+1);" onhover="tween(alpha,1.0);" onout="tween(alpha,0.25);" ondown.touch="onhover();" onup.touch="onout();">
    <layer name="skin_btn_next_fs_icon" style="skin_base" crop="64|64|64|64" align="center" scale="0.5" enabled="false" />
</layer>
 
 
<!-- gyro plugin -->
<!-- 陀螺仪插件 -->
<plugin name="skin_gyro" keep="true" url="" html5_url="%SWFPATH%/plugins/gyro2.js" softstart="1.0" enabled="false" onavailable="skin_arrange_buttons();" devices="html5" />
 
 
<!-- skin events -->
<!-- 皮肤的事件 
onxmlcomplete XML加载完成后清除当前事件，调用第一个函数skin_startup
onnewpano 加载新场景时skin_showloading显示加载中文字 skin_update_scene_infos 根据URL重新设定初始位置等信息
onloadcomplete 加载完成后隐藏加载中文字
onidle 空闲时执行URL的信息更新
onresize 屏幕尺寸变化时执行一次skin_onresize，当每次加载新的pano时onresize也会被触发一次
onenterfullscreen onexitfullscreen 进入退出全屏时更新全屏按钮的图标
onkeydown 监听键盘事件-->
<events name="skin_events" keep="true"
        onxmlcomplete="set(events[skin_events].onxmlcomplete,null); skin_startup();"
        onnewpano="skin_showloading(true); skin_update_scene_infos(); skin_deeplinking_update_url();"
        onremovepano="skin_showloading(true);"
        onloadcomplete="skin_showloading(false);"
        onidle="skin_deeplinking_update_url();"
        onresize="skin_onresize();"
        onenterfullscreen.fullscreensupport="set(layer[skin_btn_fs].crop, '64|576|64|64');"
        onexitfullscreen.fullscreensupport="set(layer[skin_btn_fs].crop, '0|576|64|64');"
        onkeydown="skin_keydown_event();"
        />
 
 
<!-- skin actions -->
<!-- 当前皮肤的启动函数 -->
<action name="skin_startup">
 
    <!-- apply skin settings on startup -->
    <!-- 根据设置确定缩略图是否在打开时就显示，并且设定是否可拖拽，鼠标的情况下设置为滚动 -->
    if(skin_settings.thumbs,
        if(skin_settings.thumbs_opened, set(layer[skin_thumbs].state,'opened'); set(layer[skin_thumbs_container].visible,true); );
        copy(layer[skin_thumbs].draggable, skin_settings.thumbs_dragging);
        if(skin_settings.thumbs_onhoverscrolling AND device.mouse,
            set(layer[skin_thumbs].draggable, false);
            set(layer[skin_thumbs].onhover_autoscrolling, true);
          );
      );
    <!-- html5的情况下加载陀螺仪插件 -->
    if(skin_settings.gyro AND !device.desktop AND device.html5,
        copy(plugin[skin_gyro].url, plugin[skin_gyro].html5_url);
      );
    <!-- html5并且支持WebVR的情况下加载WebVR插件 -->
    if(skin_settings.webvr AND device.html5 AND device.webgl,
        copy(plugin[WebVR].url, plugin[WebVR].pluginurl);
      );
    <!-- 是否显示地图插件 -->
    if(skin_settings.maps == true,
        set(layer[skin_btn_map].visible, true);
 
        if(device.flash,
            copy(layer[skin_map].key, skin_settings.maps_bing_api_key);
            set(layer[skin_map].url, '%SWFPATH%/plugins/bingmaps.swf');
          ,
            if(skin_settings.maps_type == 'bing',
                copy(layer[skin_map].key, skin_settings.maps_bing_api_key);
                set(layer[skin_map].url, '%SWFPATH%/plugins/bingmaps.js');
              ,
                copy(layer[skin_map].key, skin_settings.maps_google_api_key);
                set(layer[skin_map].url, '%SWFPATH%/plugins/googlemaps.js');
              );
          );
      );
    <!-- 小行星入场方式，只有支持WebGL和flash的情况下才可以 -->
    if(skin_settings.littleplanetintro AND (device.webgl OR device.flash),
        skin_setup_littleplanetintro();
      );
    <!-- 增加缩略图 -->
    skin_addthumbs();
    <!-- 调用onresize -->
    skin_onresize();
    <!-- skin_updatescroll -->
    skin_updatescroll();
    <!-- 显示下方控制条 -->
    set(layer[skin_layer].visible, true);
</action>
 
<!-- 增加缩略图 -->
<action name="skin_addthumbs">
    if(skin_settings.thumbs == false,
        set(layer[skin_btn_thumbs].visible,false);
      ,
        copy(thumbwidth, skin_settings.thumbs_width);
        copy(thumbheight, skin_settings.thumbs_height);
        copy(thumbpadding, skin_settings.thumbs_padding);
        copy(thumbcrop, skin_settings.thumbs_crop);
 
        add(thumbxoffset, thumbwidth, thumbpadding);
        mul(thumbxcenter, thumbxoffset, 0.5);
        mul(thumbbarwidth, thumbxoffset, scene.count);
        add(thumbbarwidth, thumbpadding);
        add(thumbbarheight, thumbpadding, thumbheight);
        add(thumbbarheight, thumbpadding);
 
        if(skin_settings.thumbs_scrollindicator,
            copy(layer[skin_thumbs_scrollindicator].y, thumbbarheight);
            add(thumbbarheight, layer[skin_thumbs_scrollindicator].height);
        );
 
        copy(layer[skin_thumbs].height, thumbbarheight);
        copy(layer[skin_thumbs].width, thumbbarwidth);
 
        mul(halfheight, thumbbarheight, 0.5);
        copy(layer[skin_thumbs_scrollleft].y, halfheight);
        copy(layer[skin_thumbs_scrollright].y, halfheight);
        <!-- 遍历所有scene并且根据序号设置缩略图名称，并且根据设置添加缩略图文字 -->
        set(thumb_cnt,0);
        for(set(i,0), i LT scene.count, inc(i),
            inc(thumb_cnt);
            txtadd(thumbname,'skin_thumb_',get(i));
            addlayer(get(thumbname));
            copy(layer[get(thumbname)].url, scene[get(i)].thumburl);
            set(layer[get(thumbname)].keep, true);
            set(layer[get(thumbname)].parent, 'skin_thumbs');
            set(layer[get(thumbname)].align, lefttop);
            copy(layer[get(thumbname)].crop, thumbcrop);
            copy(layer[get(thumbname)].width, thumbwidth);
            copy(layer[get(thumbname)].height, thumbheight);
            mul(thumbx, i, thumbxoffset);
            add(thumbx, thumbpadding);
            copy(layer[get(thumbname)].x, thumbx);
            copy(layer[get(thumbname)].y, thumbpadding);
            add(scene[get(i)].thumbx, thumbx, thumbxcenter);
            copy(scene[get(i)].thumby, thumbpadding);
            set(layer[get(thumbname)].linkedscene, get(scene[get(i)].name) );
            set(layer[get(thumbname)].onclick, copy(layer[skin_thumbborder].parent, name); skin_loadscene(get(linkedscene),get(skin_settings.loadscene_blend)); );
            if(skin_settings.tooltips_thumbs,
                set(layer[get(thumbname)].tooltip, get(scene[get(i)].title) );
                layer[get(thumbname)].loadstyle(skin_tooltips);
              );
            if(skin_settings.thumbs_text,
                txtadd(thumbtext, 'skin_thumbtext_', get(i));
                addlayer(get(thumbtext));
                layer[get(thumbtext)].loadstyle(skin_thumbtext_style);
                set(layer[get(thumbtext)].keep, true);
                set(layer[get(thumbtext)].parent, get(thumbname));
                set(layer[get(thumbtext)].html, get(scene[get(i)].title));
              );
           );
 
        if(thumb_cnt == 1,
            set(layer[skin_thumbs].align, 'lefttop');
          );
      );
</action>
 
<!-- 设置地图热点 -->
<action name="skin_addmapspots">
    for(set(i,0), i LT scene.count, inc(i),
        if(scene[get(i)].lat,
            txtadd(spotname, 'spot', get(i));
            txtadd(spotclickevent, 'skin_hidetooltips(); activatespot(',get(spotname),'); skin_loadscene(', get(scene[get(i)].name), ',get(skin_settings.loadscene_blend)); skin_updatescroll(); delayedcall(0.5,skin_showmap(false));');
            copy(scene[get(i)].mapspotname, spotname);
            addspot(get(spotname), get(scene[get(i)].lat), get(scene[get(i)].lng), get(scene[get(i)].heading), false, get(spotclickevent), null);
            if(skin_settings.tooltips_mapspots,
                set(layer[skin_map].spot[get(spotname)].tooltip, get(scene[get(i)].title) );
                txtadd(layer[skin_map].spot[get(spotname)].onover, 'set(hovering,true);',  get(style[skin_tooltips].onover) );
                txtadd(layer[skin_map].spot[get(spotname)].onout,  'set(hovering,false);', get(style[skin_tooltips].onout)  );
              );
          );
      );
 
    if(xml.scene != null,
        activatespot( get(scene[get(xml.scene)].mapspotname) );
      ,
        activatespot(spot0);
      );
 
    <!-- zoom and pan the map to see all spots at the same time -->
    zoomToSpotsExtent();
</action>
 
<!-- 小行星入场方式 -->
<action name="skin_setup_littleplanetintro">
    copy(lp_scene, xml.scene);
    copy(lp_hlookat, view.hlookat);
    copy(lp_vlookat, view.vlookat);
    copy(lp_fov, view.fov);
    copy(lp_fovmax, view.fovmax);
    copy(lp_limitview, view.limitview);
    set(view.fovmax, 170);
    set(view.limitview, lookto);
    set(view.vlookatmin, 90);
    set(view.vlookatmax, 90);
    lookat(calc(lp_hlookat - 180), 90, 150, 1, 0, 0);
    set(events[lp_events].onloadcomplete,
        delayedcall(0.5,
            if(lp_scene === xml.scene,
                set(control.usercontrol, off);
                copy(view.limitview, lp_limitview);
                set(view.vlookatmin, null);
                set(view.vlookatmax, null);
                tween(view.hlookat|view.vlookat|view.fov|view.distortion, calc('' + lp_hlookat + '|' + lp_vlookat + '|' + lp_fov + '|' + 0.0),
                    3.0, easeOutQuad,
                    set(control.usercontrol, all);
                    tween(view.fovmax, get(lp_fovmax));
                    );
              );
          );
      );
</action>
 
<!-- 跳转到指定的视角，VR模式下要同时更新切换热点的位置 -->
<action name="skin_lookat">
    if(webvr.isenabled,
        <!-- adjust the VR prev/next hotspots for the view change -->
        calc(hlookat_offset, %1 - view.hlookat);
        add(hotspot[webvr_prev_scene].ath, hlookat_offset);
        add(hotspot[webvr_next_scene].ath, hlookat_offset);
      );
    if(plugin[skin_gyro].enabled,
        <!-- reset the gyro tracking -->
        plugin[skin_gyro].resetsensor(%1);
      );
    <!-- change the view -->
    lookat(%1, %2, %3);
</action>
 
<!-- 皮肤重置位置 -->
<action name="skin_onresize">
    mul(mh, area.pixelheight, -1);
    if(layer[skin_thumbs].state == 'opened', add(mh,layer[skin_thumbs].height); );
    if(layer[skin_map].state    == 'opened', sub(hh,area.pixelheight,skin_settings.controlbar_offset); sub(hh,layer[skin_control_bar].height); sub(hh,32); add(mh,hh); add(mh,skin_settings.controlbar_overlap); sub(mh, layer[skin_scroll_layer].y_offset); copy(layer[skin_map].height, hh); );
    add(mh, layer[skin_scroll_layer].y_offset);
    set(layer[skin_scroll_layer].y, get(mh));
    skin_video_updateseekbarwidth();
    skin_arrange_buttons();
</action>
 
 
<!-- determine the visibility of the buttons and calculate their positions -->
<!-- 判断是否显示按钮并且计算他们的位置 -->
<action name="skin_arrange_buttons">
    <!-- 通过场景树是否大于1确定是否显示场景切换按钮 -->
    calc(show_selbuttons, scene.count GT 1);
    calc(show_thumbutton, skin_settings.thumbs == true);
    calc(show_mapbutton,  skin_settings.maps == true);
    calc(show_gyrobutton, plugin[skin_gyro].available == true AND (view.vlookatrange == 180 OR lp_scene === xml.scene));
    calc(show_vrbutton,   webvr.isavailable == true);
    calc(show_fsbutton,   device.fullscreensupport == true);
 
    set(lpos,6);
    set(cpos,0);
    if(show_gyrobutton, dec(cpos,20));
    if(show_vrbutton, dec(cpos,24));
    set(rpos,6);
    <!-- 非手机且展示宽度去除VR和陀螺仪按钮宽度后大于520时显示方向控制按钮 -->
    calc(show_dirbuttons, !device.mobile AND ((area.pixelwidth + 2*cpos) GT 520));
 
    copy(layer[skin_btn_navi].visible, show_dirbuttons);
 
    copy(layer[skin_btn_prev].visible, show_selbuttons);
    copy(layer[skin_btn_next].visible, show_selbuttons);
    if(show_selbuttons, inc(lpos,44); inc(rpos,44); );
 
    copy(layer[skin_btn_thumbs].visible, show_thumbutton);
    copy(layer[skin_btn_thumbs].x, lpos);
    if(show_thumbutton, inc(lpos,40));
 
    copy(layer[skin_btn_map].visible, show_mapbutton);
    copy(layer[skin_btn_map].x, lpos);
    if(show_mapbutton, inc(lpos,40));
    <!-- 如果贤惠方向控制按钮需要重新设置按钮的列方式 -->
    if(show_dirbuttons,
        copy(layer[skin_btn_navi].x, cpos);
        inc(cpos,140);
 
        set(layer[skin_btn_gyro].align, center);
        copy(layer[skin_btn_gyro].visible, show_gyrobutton);
        copy(layer[skin_btn_gyro].x, cpos);
        if(show_gyrobutton, inc(cpos,48));
 
        set(layer[skin_btn_vr].align, center);
        copy(layer[skin_btn_vr].visible, show_vrbutton);
        copy(layer[skin_btn_vr].x, cpos);
        if(show_vrbutton, inc(cpos,80));
      ,
        set(layer[skin_btn_gyro].align, left);
        copy(layer[skin_btn_gyro].visible, show_gyrobutton);
        copy(layer[skin_btn_gyro].x, lpos);
        if(show_gyrobutton, inc(lpos,40));
 
        set(layer[skin_btn_vr].align, left);
        copy(layer[skin_btn_vr].visible, show_vrbutton);
        copy(layer[skin_btn_vr].x, lpos);
        if(show_vrbutton, inc(lpos,80));
      );
 
    copy(layer[skin_btn_hide].x, rpos);
    inc(rpos,40);
 
    copy(layer[skin_btn_fs].visible, show_fsbutton);
    copy(layer[skin_btn_fs].x, rpos);
    if(show_fsbutton, inc(rpos,40));
</action>
 
<!-- 将当前的scene缩略图设置到正中央 -->
<action name="skin_updatescroll">
    if(layer[skin_thumbs].loaded,
        set(cursceneindex, 0);
        if(xml.scene, copy(cursceneindex, scene[get(xml.scene)].index));
        layer[skin_thumbs].setcenter(get(scene[get(cursceneindex)].thumbx), get(scene[get(cursceneindex)].thumby));
      );
</action>
 
<!-- 更新滑动组件 -->
<action name="skin_updatethumbscroll">
    copy(padding,skin_settings.thumbs_padding);
 
    if(skin_settings.thumbs_scrollbuttons,
        if(loverflow GT 0, set(layer[skin_thumbs_scrollleft].visible,true),  set(layer[skin_thumbs_scrollleft].visible,false) );
        if(roverflow GT 0, set(layer[skin_thumbs_scrollright].visible,true), set(layer[skin_thumbs_scrollright].visible,false) );
      );
 
    if(skin_settings.thumbs_scrollindicator,
        if(woverflow GT 0,
            set(layer[skin_thumbs_scrollindicator].visible,true);
            sub(iw,pixelwidth,woverflow);
            div(pw,iw,pixelwidth);
            div(px,loverflow,woverflow);
            mul(pw,iw);
            copy(layer[skin_thumbs_scrollindicator].width,pw);
            sub(iw,pw);
            sub(iw,padding);
            sub(iw,padding);
            mul(px,iw);
            add(px,padding);
            copy(layer[skin_thumbs_scrollindicator].x,px);
          ,
            set(layer[skin_thumbs_scrollindicator].visible,false);
          );
      );
</action>
 
<!-- 更新场景信息 -->
<action name="skin_update_scene_infos">
    if(xml.scene !== null AND scene[get(xml.scene)].index GE 0,
        <!-- 设置场景名称 -->
        if(skin_settings.title,
            if(title, txtadd(layer[skin_title].html, get(title), ' - ', get(scene[get(xml.scene)].title) ); , copy(layer[skin_title].html, scene[get(xml.scene)].title ); );
            delayedcall(0.1, set(layer[skin_title].visible,true) );
          );
        <!-- 如果不循环根据当前场景的序号设置切换按钮显示 -->
        if(skin_settings.thumbs_loop == false,
            if(scene[get(xml.scene)].index GT 0,
                set(layer[skin_btn_prev].enabled, true);
                set(layer[skin_btn_prev].alpha, 1.0);
              ,
                set(layer[skin_btn_prev].enabled, false);
                set(layer[skin_btn_prev].alpha, 0.3);
              );
 
            sub(lastsceneindex, scene.count, 1);
            if(scene[get(xml.scene)].index LT lastsceneindex,
                set(layer[skin_btn_next].enabled, true);
                set(layer[skin_btn_next].alpha, 1.0);
              ,
                set(layer[skin_btn_next].enabled, false);
                set(layer[skin_btn_next].alpha, 0.3);
              );
          ,
            if(scene.count GT 1,
                set(layer[skin_btn_prev].enabled, true);
                set(layer[skin_btn_prev].alpha, 1.0);
                set(layer[skin_btn_next].enabled, true);
                set(layer[skin_btn_next].alpha, 1.0);
              ,
                set(layer[skin_btn_prev].enabled, false);
                set(layer[skin_btn_prev].alpha, 0.3);
                set(layer[skin_btn_next].enabled, false);
                set(layer[skin_btn_next].alpha, 0.3);
              );
          );
 
        if(scene.count GT 1,
            set(layer[skin_btn_prev_fs].visible, true);
            set(layer[skin_btn_next_fs].visible, true);
          ,
            set(layer[skin_btn_prev_fs].visible, false);
            set(layer[skin_btn_next_fs].visible, false);
          );
        <!-- 设置当前场景的缩略图为选中式样 -->
        txtadd(parentname, 'skin_thumb_', get(scene[get(xml.scene)].index));
        if(layer[get(parentname)],
            set(layer[skin_thumbborder].parent, get(parentname));
            set(layer[skin_thumbborder].visible, true);
          ,
            set(layer[skin_thumbborder].visible, false);
          );
 
        if(scene[get(xml.scene)].mapspotname,
            layer[skin_map].activatespot(get(scene[get(xml.scene)].mapspotname));
            layer[skin_map].pantospot(get(scene[get(xml.scene)].mapspotname));
          );
        <!-- 设置陀螺仪按钮是否显示 -->
        if(plugin[skin_gyro].isavailable == true AND view.vlookatrange == 180,
            set(layer[skin_btn_gyro].visible, true);
          ,
            set(layer[skin_btn_gyro].visible, false)
          );
        <!-- 设置反弹效果 -->
        if(view.vlookatrange LT 180,
            if(backup_control_bouncinglimits === null,
                copy(backup_control_bouncinglimits, control.bouncinglimits);
              );
            set(control.bouncinglimits, false);
          ,
            if(backup_control_bouncinglimits !== null,
                copy(control.bouncinglimits, backup_control_bouncinglimits);
              );
          );
        <!-- 如果当前场景为视频则加载视频控制条 -->
        if(scene[get(xml.scene)].isvideopano AND plugin[video] !== null,
            skin_video_addcontrols();
          ,
            skin_video_removecontrols();
          );
      );
</action>
 
<!-- 跳转到某一指定scene 参数为scene的序号-->
<action name="skin_gotoscene">
    if(scene[%1],
        copy(cursceneindex, scene[get(xml.scene)].index);
        copy(newsceneindex, scene[%1].index);
        skin_loadscene(get(newsceneindex), calc(newsceneindex LT cursceneindex ? skin_settings.loadscene_blend_prev : (newsceneindex GT cursceneindex ? skin_settings.loadscene_blend_next : skin_settings.loadscene_blend)) );
      );
</action>
 
 
<!-- 显示下一个场景（不循环） -->
<action name="skin_nextscene">
    add(newsceneindex, scene[get(xml.scene)].index, %1);
    if(newsceneindex GE 0 AND newsceneindex LT scene.count,
        skin_loadscene(get(newsceneindex), calc(%1 LT 0 ? skin_settings.loadscene_blend_prev : skin_settings.loadscene_blend_next));
      );
</action>
 
<!-- 显示下一个场景（循环） -->
<action name="skin_nextscene_loop">
    add(newsceneindex, scene[get(xml.scene)].index, %1);
    sub(lastsceneindex, scene.count, 1);
    if(newsceneindex LT 0, copy(newsceneindex,lastsceneindex));
    if(newsceneindex GT lastsceneindex, set(newsceneindex,0));
    skin_loadscene(get(newsceneindex), calc(%1 LT 0 ? skin_settings.loadscene_blend_prev : skin_settings.loadscene_blend_next));
</action>
 
 
<!-- skin_loadscene(scenenameorindex, blendmode) -->
<!-- 加载场景如果只有一个场景就WebVR的按钮隐藏，并且在场景缩略图上加上边框效果，blendmode为场景切换动画 -->
<action name="skin_loadscene">
    if(webvr.isenabled AND scene.count GT 1,
        set(hotspot[webvr_prev_scene].visible, false);
        set(hotspot[webvr_next_scene].visible, false);
      );
 
    txtadd(layer[skin_thumbborder].parent, 'skin_thumb_', get(scene[%1].index));
    layer[skin_thumbs].scrolltocenter(get(scene[%1].thumbx), get(scene[%1].thumby));
    loadscene(get(scene[%1].name), null, get(skin_settings.loadscene_flags), %2);
</action>
 
<!-- 加载文字是否显示 -->
<action name="skin_showloading">
    if(display.stereo == true,
        set(layer[skin_loadingtext].visible, false);
      ,
        set(layer[skin_loadingtext].visible, %1);
      );
</action>
 
 
<!-- 隐藏tips -->
<action name="skin_hidetooltips">
    set(layer[skin_tooltip].alpha,0.0);
    set(layer[skin_tooltip].visible,false);
</action>
 
<!-- 按钮的点击效果，在点击的按钮下添加一个Child -->
<action name="skin_buttonglow">
    if('%1' !== 'null',
        set(strength,0.7);
        if(%2 != null, set(strength,%2));
        set(layer[skin_buttonglow].parent, %1);
        set(layer[skin_buttonglow].visible, true);
        tween(layer[skin_buttonglow].alpha, get(strength), 0.07);
      ,
        tween(layer[skin_buttonglow].alpha, 0.0, 0.1, default,
            set(layer[skin_buttonglow].parent, null);
            set(layer[skin_buttonglow].visible, false);
          );
      );
</action>
 
<!-- 设置关闭打开的距离 -->
<action name="skin_calc_opened_closed">
    if(layer[get(name)].y_closed === null,
        set(layer[get(name)].y_opened, get(layer[get(name)].y));
        set(layer[get(name)].y_closed, calc(layer[get(name)].y - skin_settings.controlbar_offset - skin_settings.controlbar_height + skin_settings.controlbar_offset_closed));
      );
</action>
 
<!-- 隐藏控制条，首先隐藏上方布局，其次底部最后控制条 -->
<action name="skin_hideskin">
    callwith(layer[skin_scroll_window],   skin_calc_opened_closed() );
    callwith(layer[skin_splitter_bottom], skin_calc_opened_closed() );
    callwith(layer[skin_control_bar],     skin_calc_opened_closed() );
 
    if(layer[skin_map].state    != 'closed', skin_showmap(false);    wait(0.40); );
    if(layer[skin_thumbs].state != 'closed', skin_showthumbs(false); wait(0.25); );
 
    set(hidetime, calc('%1' == 'instant' ? 0.0 : 0.5));
    tween(layer[skin_scroll_window].y,   get(layer[skin_scroll_window  ].y_closed), get(hidetime));
    tween(layer[skin_splitter_bottom].y, get(layer[skin_splitter_bottom].y_closed), get(hidetime));
    tween(layer[skin_control_bar].y,     get(layer[skin_control_bar    ].y_closed), get(hidetime));
 
    tween(layer[skin_btn_prev_fs].x, 0, get(hidetime));
    tween(layer[skin_btn_next_fs].x, 0, get(hidetime));
 
    if(layer[skin_logo], tween(layer[skin_logo].alpha, 0.0, 0.5, default, set(layer[skin_logo].visible,false)); );
 
    stopdelayedcall(skin_btn_show_alpha);
    set(layer[skin_btn_show].visible, true);
    delayedcall(skin_btn_show_alpha, get(hidetime), tween(layer[skin_btn_show].alpha, 0.25, 0.25); );
</action>
 
<!-- 显示隐藏的控制条 -->
<action name="skin_showskin">
    tween(layer[skin_scroll_window  ].y, get(layer[skin_scroll_window  ].y_opened));
    tween(layer[skin_splitter_bottom].y, get(layer[skin_splitter_bottom].y_opened));
    tween(layer[skin_control_bar    ].y, get(layer[skin_control_bar    ].y_opened));
 
    tween(layer[skin_btn_prev_fs].x, -50);
    tween(layer[skin_btn_next_fs].x, -50);
 
    if(layer[skin_logo], set(layer[skin_logo].visible,true); tween(layer[skin_logo].alpha, 1.0); );
 
    stopdelayedcall(skin_btn_show_alpha);
    set(layer[skin_btn_show].visible, false);
    delayedcall(skin_btn_show_alpha, 0.25, tween(layer[skin_btn_show].alpha, 0.0, 0.0); );
</action>
 
<!-- 显示缩略图， 首先判断是否已经关闭，layer[skin_scroll_layer].pixelheight=area.pixelheight的值为当前窗口的高度
假设当前窗口高度为640 1.640*-1=-640 2.减去（layer[skin_thumbs].height）缩略图的高度100 -640+100=-540 3.减去（y_offset）背景重叠区域大小 10 -540+10=-530
4. layer[skin_scroll_layer].y大小为负的area.pixelheight+y_offset一开始onresize时设定 则变化范围为 -630 到-530 
详细参照http://krpano.com/docu/xml/pluginalignment.png这张图，备注下对于xy属性，默认向下为Y的正向向右为X 的正向，edge未设定时默认和align一个值-->
<action name="skin_showthumbs">
    if(%1 == null, if(layer[skin_thumbs].state == 'closed', set(show,true), set(show,false)); , set(show,%1); );
    mul(mh, layer[skin_scroll_layer].pixelheight, -1);
 
    if(show,
        set(layer[skin_thumbs].state, 'opened');
        tween(layer[skin_thumbs].alpha, 1.0, 0.25);
        add(mh, layer[skin_thumbs].height);
        add(mh, layer[skin_scroll_layer].y_offset);
        tween(layer[skin_scroll_layer].y, get(mh), 0.5, easeOutQuint);
        set(layer[skin_thumbs_container].visible, true);
        tween(layer[skin_thumbs_container].alpha, 1.0, 0.25);
        tween(layer[skin_map].alpha, 0.0, 0.25, default, set(layer[skin_map].visible,false));
      ,
        set(layer[skin_thumbs].state, 'closed');
        tween(layer[skin_thumbs].alpha, 0.0, 0.25, easeOutQuint);
        add(mh, layer[skin_scroll_layer].y_offset);
        tween(layer[skin_scroll_layer].y, get(mh), 0.5, easeOutQuint, set(layer[skin_thumbs_container].visible, false););
      );
</action>
 
<!-- 显示地图 -->
<action name="skin_showmap">
    if(%1 == null, if(layer[skin_map].state == 'closed', set(show,true), set(show,false)); , set(show,%1); );
    mul(mh, layer[skin_scroll_layer].pixelheight, -1);
    if(show,
        tween(layer[skin_thumbs_container].alpha, 0.0, 0.25, default, set(layer[skin_thumbs_container].visible,false));
        set(layer[skin_map].visible, true);
        tween(layer[skin_map].alpha, 1.0, 0.25);
        set(layer[skin_map].state, 'opened');
        sub(hh,area.pixelheight,skin_settings.controlbar_offset);
        sub(hh,layer[skin_control_bar].height);
        sub(hh,32);
        add(mh,hh);
        sub(hh,skin_settings.controlbar_overlap);
        copy(layer[skin_map].height, hh);
        tween(layer[skin_scroll_layer].y, get(mh), 0.5, easeOutQuint);
      ,
        if(layer[skin_map].state != 'closed',
            set(layer[skin_map].state, 'closed');
            add(mh, layer[skin_scroll_layer].y_offset);
            tween(layer[skin_map].alpha, 0.0, 0.5, easeOutQuint);
            tween(layer[skin_scroll_layer].y, get(mh), 0.5, easeOutQuint, set(layer[skin_map].visible,false) );
          );
      );
</action>
 
<!-- 绑定键盘事件 -->
<action name="skin_keydown_event">
    if(keycode == 33, skin_nextscene_loop(-1) );                <!-- Page Up   - previous scene -->
    if(keycode == 34, skin_nextscene_loop(+1) );                <!-- Page Dowm - next scene -->
    if(keycode == 35, skin_gotoscene(calc(scene.count-1)) );    <!-- End       - last scene -->
    if(keycode == 36, skin_gotoscene(0) );                      <!-- Home/Pos1 - first scene -->
</action>
 
<!-- 如果使用深度链接功能调用skin_deeplinking_update_url_process获取链接参数并设置 -->
<action name="skin_deeplinking_update_url">
    if(skin_settings.deeplinking AND (!webvr OR webvr.isenabled === false),
        delayedcall(skin_deeplinking_update, calc(%1 == null ? 0.1 : %1), skin_deeplinking_update_url_process() );
      );
</action>
<!-- 深度链接功能，通过URL传递场景的初始位置等信息，重新设定到新的场景上 -->
<action name="skin_deeplinking_update_url_process">
    <!-- 获取当前的URL -->
    copy(adr, browser.location);
    <!-- 获取？后的参数信息 -->
    indexoftxt(qi, get(adr), '?');
    if(qi GT 0, subtxt(adr, adr, 0, get(qi)));
    copy(si, scene[get(xml.scene)].index);
    copy(h, view.hlookat);
    copy(v, view.vlookat);
    copy(f, view.fov);
    copy(d, view.distortion);
    copy(a, view.architectural);
    clamp(d, 0.0, 1.0);
    clamp(a, 0.0, 1.0);
    set(pp, calc(f LT 10 ? 6 : 2));
    roundval(h, get(pp));
    roundval(v, get(pp));
    roundval(f, get(pp));
    roundval(d, 2);
    roundval(a, 1);
    set(adr, calc(adr + '?startscene=' + si + '&amp;startactions=lookat('+h+','+v+','+f+','+d+','+a+');'));
    js( history.replaceState(null, document.title, get(adr)); );
</action>
 
 
<!-- reload the scene when there is a special image for VR -->
<!-- 如果scene标签有havevrimage属性，进入VR重载界面 -->
<action name="skin_reloadscene_webvr">
    delayedcall(0.1,
        if(scene[get(xml.scene)].havevrimage,
            copy(keeplookingdirection_backup, skin_settings.webvr_gyro_keeplookingdirection);
            set(skin_settings.webvr_gyro_keeplookingdirection, true);
            loadscene(get(xml.scene), null, MERGE|KEEPVIEW|KEEPMOVING|KEEPHOTSPOTS|NOPREVIEW, BLEND(0.5));
            copy(skin_settings.webvr_gyro_keeplookingdirection, keeplookingdirection_backup);
            delete(keeplookingdirection_backup);
          );
      );
</action>
 
 
<!-- videopano support - http://krpano.com/plugins/videoplayer/ -->
<!-- 加载视频控制条 -->
<action name="skin_video_addcontrols">
    set(events[skin_events].onclick, skin_video_clickevent() );
 
    set(plugin[video].onvideoready, skin_video_updatestate() );
    set(plugin[video].onvideoplay, skin_video_updatestate() );
    set(plugin[video].onvideopaused, skin_video_updatestate() );
    set(plugin[video].onvideocomplete, skin_video_updatestate() );
 
    if(plugin[video].ispaused AND plugin[video].pausedonstart,
        set(layer[skin_video_playpause].state, 'visible');
        set(layer[skin_video_playpause].enabled, true);
        tween(layer[skin_video_playpause].alpha, 1.0);
      );
 
    delayedcall(skin_video_delayedvisible, 0.25, set(layer[skin_video_controls].visible, true) );
 
    skin_video_updateseekbarwidth();
    set(layer[skin_video_seekpos].x,0);
    set(layer[skin_video_loadbar].width,0);
 
    setinterval(skin_video_seek_updates, 0.5, skin_video_updatetime() );
</action>
<!-- 去除视频控制条 -->
<action name="skin_video_removecontrols">
    stopdelayedcall(skin_video_delayedvisible);
 
    set(events[skin_events].onclick, null);
 
    set(layer[skin_video_playpause].alpha, 0.0);
    set(layer[skin_video_controls].visible, false);
 
    clearinterval(skin_video_seek_updates);
</action>
<!-- 实时更新seek的进度和时间显示 -->
<action name="skin_video_updatetime">
    copy(t1, plugin[video].time);
    copy(t2, plugin[video].totaltime);
    if(%1 !== null, calc(t1, %1 * t2); );
    div(t1_min, t1, 60);
    mod(t1_sec, t1, 60);
    Math.floor(t1_min);
    Math.floor(t1_sec);
    div(t2_min, t2, 60);
    mod(t2_sec, t2, 60);
    Math.floor(t2_min);
    Math.floor(t2_sec);
    calc(layer[skin_video_time].html, t1_min + ':' + (t1_sec LT 10 ? '0' : '') + t1_sec + ' / ' + t2_min + ':' + (t2_sec LT 10 ? '0' : '') + t2_sec);
    calc(layer[skin_video_seekpos].x, (t1 / t2 * 100) + '%');
    calc(layer[skin_video_loadbar].width, (plugin[video].loadedbytes / plugin[video].totalbytes * 100) + '%');
</action>
<!-- 更新视频进度空间的宽度 -->
<action name="skin_video_updateseekbarwidth">
    if(skin_settings.title,
        calc(layer[skin_video_seekbar_container].width, 0 - (32 + layer[skin_title].pixelwidth + layer[skin_video_time].pixelwidth));
        calc(layer[skin_video_seekbar_container].x, layer[skin_title].pixelwidth + 16);
      ,
        calc(layer[skin_video_seekbar_container].width, 0 - (24 + layer[skin_video_time].pixelwidth));
        set(layer[skin_video_seekbar_container].x, 8);
      );
</action>
<!-- 跳转到指定的视频进度 -->
<action name="skin_video_ondownseeking">
    asyncloop(pressed,
        screentolayer(skin_video_seekbar, mouse.stagex,mouse.stagey, lx,ly);
        calc(seekpos, lx / layer[skin_video_seekbar].pixelwidth);
        clamp(seekpos, 0.0, 1.0);
        skin_video_updatetime(seekpos);
      ,
        plugin[video].seek(calc((seekpos * 100) + '%'));
      );
</action>
<!-- 暂停或者显示时的图层 -->
<layer name="skin_video_playpause" keep="true"
         style="skin_base|skin_glow" crop="0|640|64|64" scale="0.75"
         align="center" alpha="0.0" autoalpha="true"
         state="hidden"
         onclick="skin_video_playpause_click();"
         />
<!-- 状态变更时更新 -->
<action name="skin_video_updatestate">
    calc(layer[skin_video_playpause].crop, plugin[video].ispaused ? '0|640|64|64' : '64|640|64|64');
    if(plugin[video].iscomplete,
        set(layer[skin_video_playpause].state, 'visible');
        tween(layer[skin_video_playpause].alpha, 1.0);
      );
</action>
<!-- 点击暂停按钮 -->
<action name="skin_video_playpause_click">
    if(plugin[video].ispaused,
        plugin[video].play();
        set(layer[skin_video_playpause].state, 'hidden');
        tween(layer[skin_video_playpause].alpha, 0.0);
      ,
        plugin[video].pause();
        set(layer[skin_video_playpause].state, 'visible');
        tween(layer[skin_video_playpause].alpha, 1.0);
        delayedcall(autohide_pp, 2.0, set(layer[skin_video_playpause].state,'hidden'); tween(layer[skin_video_playpause].alpha, 0.0); );
      );
</action>
<!-- 点击屏幕的事件触发视频播放和暂停 -->
<action name="skin_video_clickevent">
    stopdelayedcall(autohide_pp);
 
    switch(layer[skin_video_playpause].state, 'visible', 'hidden');
 
    if(layer[skin_video_playpause].state == 'hidden',
        tween(layer[skin_video_playpause].alpha, 0.0);
      ,
        tween(layer[skin_video_playpause].alpha, 1.0);
        delayedcall(autohide_pp, 2.0, set(layer[skin_video_playpause].state,'hidden'); tween(layer[skin_video_playpause].alpha, 0.0); );
      );
</action>
 
 
<!-- context menu - http://krpano.com/docu/xml/#contextmenu -->
<!-- 右键按钮菜单 -->
<contextmenu>
    <item name="kr" caption="Krpano" onclick="openurl('http://www.krpano.com',_blank);"/>
    <item name="fs" caption="FULLSCREEN" />
    <item name="cc" caption="Change Controlmode" onclick="skin_changecontrolmode();"  separator="true" />
    <item name="nv" caption="Normal View"        onclick="skin_view_normal();"        showif="view.vlookatrange == 180" separator="true"      />
    <item name="fv" caption="Fisheye View"       onclick="skin_view_fisheye();"       showif="view.vlookatrange == 180" devices="flash|webgl" />
    <item name="sv" caption="Stereographic View" onclick="skin_view_stereographic();" showif="view.vlookatrange == 180" devices="flash|webgl" />
    <item name="av" caption="Architectural View" onclick="skin_view_architectural();" showif="view.vlookatrange == 180"                       />
    <item name="pv" caption="Pannini View"       onclick="skin_view_pannini();"       showif="view.vlookatrange == 180" devices="flash|webgl" />
    <item name="lp" caption="Little Planet View" onclick="skin_view_littleplanet();"  showif="view.vlookatrange == 180" devices="flash|webgl" />
</contextmenu>
 
<!-- 点击改变控制方式函数 -->
<action name="skin_changecontrolmode">
    switch(control.mouse, moveto, drag);
    switch(control.touch, moveto, drag);
</action>
<!-- 以下为不同的全景显示模式 -->
<action name="skin_view_look_straight">
    if(view.vlookat LT -80 OR view.vlookat GT +80,
        tween(view.vlookat, 0.0, 1.0, easeInOutSine);
        tween(view.fov,     100, distance(150,0.8));
      );
    skin_deeplinking_update_url(1.0);
</action>
 
<action name="skin_view_normal">
    skin_view_look_straight();
    tween(view.architectural, 0.0, distance(1.0,0.5));
    tween(view.pannini,       0.0, distance(1.0,0.5));
    tween(view.distortion,    0.0, distance(1.0,0.5));
</action>
 
<action name="skin_view_fisheye">
    skin_view_look_straight();
    tween(view.architectural, 0.0,  distance(1.0,0.5));
    tween(view.pannini,       0.0,  distance(1.0,0.5));
    tween(view.distortion,    0.35, distance(1.0,0.5));
</action>
 
<action name="skin_view_architectural">
    skin_view_look_straight();
    tween(view.architectural, 1.0, distance(1.0,0.5));
    tween(view.pannini,       0.0, distance(1.0,0.5));
    tween(view.distortion,    0.0, distance(1.0,0.5));
</action>
 
<action name="skin_view_stereographic">
    skin_view_look_straight();
    tween(view.architectural, 0.0, distance(1.0,0.5));
    tween(view.pannini,       0.0, distance(1.0,0.5));
    tween(view.distortion,    1.0, distance(1.0,0.8));
</action>
 
<action name="skin_view_pannini">
    skin_view_look_straight();
    tween(view.architectural, 0.0, distance(1.0,0.5));
    tween(view.pannini,       1.0, distance(1.0,0.8));
    if(view.distortion LT 0.1,
        tween(view.distortion, 1.0, distance(1.0,0.8));
      );
</action>
 
<action name="skin_view_littleplanet">
    tween(view.architectural, 0.0, distance(1.0,0.5));
    tween(view.pannini,       0.0, distance(1.0,0.5));
    tween(view.distortion,    1.0, distance(1.0,0.8));
    tween(view.fov,           150, distance(150,0.8));
    tween(view.vlookat,        90, distance(100,0.8));
    add(new_hlookat, view.hlookat, 123.0);
    tween(view.hlookat, get(new_hlookat), distance(100,0.8));
    skin_deeplinking_update_url(1.0);
</action>
```
