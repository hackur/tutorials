---
tag: info
src: info-02-setup.html
title: Webduino Initialization Setup
banner: info-02-01.jpg
img: info-02-01s.jpg
date: 20150420
---

<!-- @@master  = ../../_layout.html-->

<!-- @@block  =  meta-->

<title>Webduino Initialization Setup :::: Webduino = Web × Arduino</title>

<meta name="description" content="The most important thing before execute Webduino is doing initialization set-up.  The purpose of initialization is making Webduino development kit connect to internet automatically.  The same as what we do on a new mobile phone, we need to setup Wi-Fi on the phone to browse internet via home Wi-Fi. ">

<meta itemprop="description" content="The most important thing before execute Webduino is doing initialization set-up.  The purpose of initialization is making Webduino development kit connect to internet automatically.  The same as what we do on a new mobile phone, we need to setup Wi-Fi on the phone to browse internet via home Wi-Fi. ">

<meta property="og:description" content="The most important thing before execute Webduino is doing initialization set-up.  The purpose of initialization is making Webduino development kit connect to internet automatically.  The same as what we do on a new mobile phone, we need to setup Wi-Fi on the phone to browse internet via home Wi-Fi. ">

<meta property="og:title" content="Webduino Initialization Setup" >

<meta property="og:url" content="https://webduino.io/tutorials/info-02-setup.html">

<meta property="og:image" content="https://webduino.io/img/tutorials/info-02-01s.jpg">

<meta itemprop="image" content="https://webduino.io/img/tutorials/info-02-01s.jpg">

<include src="../_include-tutorials.html"></include>

<!-- @@close-->

<!-- @@block  =  preAndNext-->

<include src="../_include-tutorials-content.html"></include>

<!-- @@close-->



<!-- @@block  =  tutorials-->
#Webduino Initialization Setup

The most important thing before execute Webduino is doing initialization set-up.  The purpose of initialization is making Webduino development kit connect to internet automatically.  The same as what we do on a new mobile phone, we need to setup Wi-Fi on the phone to browse internet via home Wi-Fi. 

##Webduino Initialization Step by Step

- ###1. Start Initialization

	There is a switch on Webduino development board. Switch to STA pattern, Turn the power on and start initialization set-up.

	![Webduino - 開始進行初始化](../../img/tutorials/info-02-09.jpg)

- ###2. Search Webduino Development Kit

	Use Wi-Fi on a computer or a portable device to search the SSID name of Webduino Development Kit and key-in password (default is 12345678).  Then, this computer or portable device can connect to Webduino.  The SSID of Webduino Development Kit is used to be [wa...] (such as wa101).

	![Webduino - 使用 Wi-Fi 搜尋 Webduino 開發板](../../img/tutorials/info-02-04.jpg)

- ###3. Connect to Webduino Development Kit to setup

	Use browser Chrome or Safari and type-in web address http://192.168.4.1, you can open the set-up page of Webduino Development Kit.  Type-in the SSID and PASSWORD of your shared Wi-Fi base station at home, in office or on a portable device. (SSID for Wi-Fi base station has a max. length of 14 characters,  letters and numbers)

	![Webduino - 連線 Webduino 開發板進行設定](../../img/tutorials/info-02-07.jpg)


- ###4. Reboot Webduino Development Kit

	After type-in SSID and PASSWORD, press ‘sending’. When ‘OK’ shows, Webduino is initialized and can be connect to the Wi-Fi based station shared at home, in office or on portable device.  Remove power on the Development Kit and switch to AP pattern.  Then connect power and reboot.  If no ‘OK’ shows, remove power and set up again from step2.  

	![Webduino - 重啟 Webduino 開發板](../../img/tutorials/info-02-10.jpg)

- ###5. Connection Confirm

	Reboot Webduino Development Kit, then, switch to normal internet connection on computer or portable device.  Connect to https://webduino.io/device.html and type-in the name of device to check the connection.  If connection works successful, it’ll show ‘OK’.  When ‘OK’ shows, you can start playing Webduino.  If there is no correspondent Webduino Development Kit, you need to reboot Webduino Development Kit or remove power and then set up from step2.

	![Webduino - 確認連線是否成功](../../img/tutorials/info-02-06.jpg)

	There is another easier way to evaluate that a small red LED on the Kit will be extinguished when connection is successful.  However, while this red LED keeps blinking, connection is failed.  Reboot Webduino or reconnect power and start setting up from step2.
	
	![Webduino - 確認連線是否成功](../../img/tutorials/info-02-11.jpg)


- ###6. Webduino Development Kit can connect to Wi-Fi based station

	Webduino can connect to a shared Wi-Fi station at home, in office or on a portable device, and connect to cloud server automatically.  Now, let’s try to control Webduino via Wi-Fi.

<!-- @@close-->