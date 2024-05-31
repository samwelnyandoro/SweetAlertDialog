SweetAlertDialog
===================

<p align="center">
  </a>
    <a href="https://twitter.com/intent/tweet?text=Add%20sweetalert%20dialog%20GitHub%20Trophy%20on%20your%20androidapplication%0D%0A&url=https%3A%2F%2Fgithub.com%2samwelnyandoro%2Fgithub-profile-trophy">
    <img src="https://img.shields.io/twitter/url?style=social&url=https%3A%2F%2Fgithub.com%2Fryo-ma%2Fgithub-profile-trophy"/> 
  </a>
</p>
<!--<p align="center">
  You can use this service for free. I'm looking for sponsors to help us keep up with this service❤️
</p>
<p align="center">
  <a href="https://github.com/sponsors/samwelnyandoro">
    <img src="https://img.shields.io/static/v1?label=Sponsor&message=%E2%9D%A4&logo=GitHub&color=ff69b4"/> 
  </a>
</p>-->


SweetAlert for Android, a beautiful and clever alert dialog

[![Android Arsenal](https://img.shields.io/badge/Android%20Arsenal-Sweet%20Alert%20Dialog-brightgreen.svg?style=flat)](https://android-arsenal.com/details/1/1065)

Inspired by JavaScript [SweetAlert](http://tristanedwards.me/sweetalert)

**Gradle**

    repositories {
        mavenCentral()
        maven { url 'https://jitpack.io' }
    }

    dependencies {
        implementation 'com.github.samwelnyandoro:SweetAlertDialog:1.1'
    }

## Usage

show material progress

    SweetAlertDialog pDialog = new SweetAlertDialog(this, SweetAlertDialog.PROGRESS_TYPE);
    pDialog.getProgressHelper().setBarColor(Color.parseColor("#A5DC86"));
    pDialog.setTitleText("Loading");
    pDialog.setCancelable(false);
    pDialog.show();
    
 ![image](https://github.com/pedant/sweet-alert-dialog/raw/master/play_progress.gif)
 
 ## License

    The MIT License (MIT)

    Copyright (c) 2022 Samwel(https://samwelnyandoro1.netlify.app)

    Permission is hereby granted, free of charge, to any person obtaining a copy
    of this software and associated documentation files (the "Software"), to deal
    in the Software without restriction, including without limitation the rights
    to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
    copies of the Software, and to permit persons to whom the Software is
    furnished to do so, subject to the following conditions:

    The above copyright notice and this permission notice shall be included in all
    copies or substantial portions of the Software.

    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
    IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
    FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
    AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
    LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
    OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
    SOFTWARE.
