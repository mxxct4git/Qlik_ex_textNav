# Qlik_ex_textNav
This is an extension which helps you jump pages you want easily. You are free to custom the text style you like in the right panel. 

The reason for developing this extension is that there are two main types of jumps required in the business, text and buttons, and we currently use 2 extensions, but their customization is not very good, so we decide to put the two together.

![pic1](https://github.com/mxxt/my_image/blob/master/WechatIMG4.png?raw=true)

![pic2](https://github.com/mxxt/my_image/blob/master/WechatIMG5.png?raw=true)

For example, you can set your font color, font size, etc in the panel, and you can also set the thickness and color of the border line, so you can get a button style.

Here we design this button in the style of Leonardo UI.

- Font Color: #595959
- Font Size: 13
- Bold
- Border Color: #B3B3B3
- Border Width: 1
- Border Radius: 3
- Border Line: Solid

![pic3](https://github.com/mxxt/my_image/blob/master/WechatIMG7.png?raw=true)

![pic4](https://github.com/mxxt/my_image/blob/master/WechatIMG8.png?raw=true)

Here we get a button: 

![pic4](https://github.com/mxxt/my_image/blob/master/WechatIMG9.png?raw=true)

In a jump event, you can choose whether to jump to any sheet under the current app or any sheet under other apps on this server(you must have viewing rights for the app you choose) or just open an external website

When you select 'Go to other app's sheet', you need to continue to select an app and a sheet, and which method you want to jump.

![pic5](https://github.com/mxxt/my_image/blob/master/WechatIMG10.png?raw=true)

If you choose 'Single Object', there will be 5 check boxes below:

![pic6](https://github.com/mxxt/my_image/blob/master/WechatIMG11.png?raw=true)

When you choose 'Jump with params', you must confirm that the field selected in the current sheet also exists on the worksheet after the jump and that the name is the same.
