Product Flavors
-----
**`Why flavors is important:`**
As an app developer, you would like to release a given app using a new brand name, logo, image and/or theme, along with some minor feature differences. Using this to maintain app very quickly.

Using multi flavors developer can easy way to build and maintain different version of app.

If you have create two flavors, let say free and paid, and two build types called debug and release, the Build Variants will be:
* `freeDebug`
* `freeRelease`
* `paidDebug`
* `paidRelease`

**Working with flavors:**
```
productFlavors {
        free {}
        paid {}
    }
```

<br/>

## Use case of Product Flavors:

- Product Flavor is very useful, when having some work or requirement like I want to multiple app in which code should be
  same but different UI, for example i want to display different google map type according to countries, so we can achieved
  that through the Product Flavors.
- We can also used like If you are implement project and you want to create different build(apk) according to environment
  like Demo, UAT, Production which is trigger to different end point server, so you can achieve that through Product Flavors.
- It is also useful, if you want to create different flavors of SDK, like SDK with all features, SDK with particular feature,
  so we can achieve that using Product Flavors.


Screenshots
-----------

![screenshot][1] ![screenshot][2] ![screenshot][3] ![screenshot][4]

[1]: ./screenshot/free.jpg
[2]: ./screenshot/paid.jpg
[3]: ./screenshot/free_paid_logo_label.jpg
[4]: ./screenshot/code_screen.jpg