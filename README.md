<?xml version="1.0" encoding="UTF-8"?>
<widget xmlns     = "http://www.w3.org/ns/widgets"
        xmlns:gap = "http://phonegap.com/ns/1.0"
        id        = "com.phonegap.hello-world"
        version   = "2.0.0">
    <name>Hello World</name>

    <description>
        Hello World sample application that responds to the deviceready event.
    </description>

    <author href="http://phonegap.com" email="support@phonegap.com">
        PhoneGap Team
    </author>

    <feature name="http://api.phonegap.com/1.0/device" />

    <preference name="phonegap-version" value="2.1.0" />
    <preference name="orientation"      value="default" />
    <preference name="target-device"    value="universal" />
    <preference name="fullscreen"       value="false" />

    <icon src="icon.png" />
    <icon src="res/icon/android/icon-36-ldpi.png"   gap:platform="android"    gap:density="ldpi" />
    <icon src="res/icon/android/icon-48-mdpi.png"   gap:platform="android"    gap:density="mdpi" />
    <icon src="res/icon/android/icon-72-hdpi.png"   gap:platform="android"    gap:density="hdpi" />
    <icon src="res/icon/android/icon-96-xhdpi.png"  gap:platform="android"    gap:density="xhdpi" />
    <icon src="res/icon/blackberry/icon-80.png"     gap:platform="blackberry" />
    <icon src="res/icon/blackberry/icon-80.png"     gap:platform="blackberry" gap:state="hover"/>
    <icon src="res/icon/ios/icon-57.png"            gap:platform="ios"        width="57" height="57" />
    <icon src="res/icon/ios/icon-72.png"            gap:platform="ios"        width="72" height="72" />
    <icon src="res/icon/ios/icon-57-2x.png"         gap:platform="ios"        width="114" height="114" />
    <icon src="res/icon/ios/icon-72-2x.png"         gap:platform="ios"        width="144" height="144" />
    <icon src="res/icon/webos/icon-64.png"          gap:platform="webos" />
    <icon src="res/icon/windows-phone/icon-48.png"  gap:platform="winphone" />
    <icon src="res/icon/windows-phone/icon-173.png" gap:platform="winphone"   gap:role="background" />

    <gap:splash src="res/screen/android/screen-ldpi-portrait.png"  gap:platform="android" gap:density="ldpi" />
    <gap:splash src="res/screen/android/screen-mdpi-portrait.png"  gap:platform="android" gap:density="mdpi" />
    <gap:splash src="res/screen/android/screen-hdpi-portrait.png"  gap:platform="android" gap:density="hdpi" />
    <gap:splash src="res/screen/android/screen-xhdpi-portrait.png" gap:platform="android" gap:density="xhdpi" />
    <gap:splash src="res/screen/blackberry/screen-225.png"         gap:platform="blackberry" />
    <gap:splash src="res/screen/ios/screen-iphone-portrait.png"    gap:platform="ios"     width="320" height="480" />
    <gap:splash src="res/screen/ios/screen-iphone-portrait-2x.png" gap:platform="ios"     width="640" height="960" />
    <gap:splash src="res/screen/ios/screen-ipad-portrait.png"      gap:platform="ios"     width="768" height="1024" />
    <gap:splash src="res/screen/ios/screen-ipad-landscape.png"     gap:platform="ios"     width="1024" height="768" />
    <gap:splash src="res/screen/windows-phone/screen-portrait.jpg" gap:platform="winphone" />
</widget>