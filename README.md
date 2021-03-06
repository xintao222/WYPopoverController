WYPopoverController
===================

WYPopoverController is for the presentation of content in popover on iPhone / iPad devices. Very customizable.

### Screenshots

---

![](https://raw.github.com/nicolaschengdev/WYPopoverController/master/screenshots/wypopover_screenshot_1.png) ![](https://raw.github.com/nicolaschengdev/WYPopoverController/master/screenshots/wypopover_screenshot_2.png) 

### Features

---

* UIAppearance support
* Works like UIPopoverController
* Rotation support
* UIStoryboard support
* Keyboard show / hide support

### UIAppearance support

---

| Property              | Type           | Default value                                                                          |
| --------------------- | -------------- | -------------------------------------------------------------------------------------: |
| tintColor             | `UIColor`      |                                                                                  *nil* |
| arrowBase             | `CGFloat`      |                                                                                     42 |
| arrowHeight           | `CGFloat`      |                                                                                     18 |
| borderWidth           | `CGFloat`      |                                                                                      6 |
| outerCornerRadius     | `CGFloat`      |                                                                                      8 |
| minOuterCornerRadius ![](https://raw.github.com/nicolaschengdev/WYPopoverController/master/screenshots/wypopover_new_ico.png)    | `CGFloat`      |                                                                                      0 |
| innerCornerRadius     | `CGFloat`      |                                                                                      6 |
| viewContentInsets     | `UIEdgeInsets` |                                                                         { 3, 0, 0, 0 } |
| strokeColor           | `UIColor`      | #262c31ff ![](https://raw.github.com/nicolaschengdev/WYPopoverController/master/screenshots/wypopover_default_strokecolor.png) |
| fillTopColor          | `UIColor`      | #373f47ff ![](https://raw.github.com/nicolaschengdev/WYPopoverController/master/screenshots/wypopover_default_filltopcolor.png) |
| fillBottomColor       | `UIColor`      | #3b434cff ![](https://raw.github.com/nicolaschengdev/WYPopoverController/master/screenshots/wypopover_default_fillbottomcolor.png) |
| glossShadowColor      | `UIColor`      | #c3c5c77f ![](https://raw.github.com/nicolaschengdev/WYPopoverController/master/screenshots/wypopover_default_glossshadowcolor.png) |
| glossShadowBlurRadius | `CGFloat`      |                                                                                      0 |
| glossShadowOffset     | `CGSize`       |                                                                             { 0, 1.5 } |
| outerShadowColor      | `UIColor`      | #000000bf ![](https://raw.github.com/nicolaschengdev/WYPopoverController/master/screenshots/wypopover_default_shadowcolor.png) |
| outerShadowBlurRadius | `CGFloat`      |                                                                                      8 |
| outerShadowOffset     | `CGSize`       |                                                                               { 0, 2 } |
| innerShadowColor      | `UIColor`      | #000000bf ![](https://raw.github.com/nicolaschengdev/WYPopoverController/master/screenshots/wypopover_default_shadowcolor.png) |
| innerShadowBlurRadius | `CGFloat`      |                                                                                      2 |
| innerShadowOffset     | `CGSize`       |                                                                               { 0, 1 } |

##### Arrow & Border

![](https://raw.github.com/nicolaschengdev/WYPopoverController/master/screenshots/appearance/small/wypopover_arrowbase.png "arrowBase: 42") , ![](https://raw.github.com/nicolaschengdev/WYPopoverController/master/screenshots/appearance/small/wypopover_arrowheight.png "arrowHeight: 18") , ![](https://raw.github.com/nicolaschengdev/WYPopoverController/master/screenshots/appearance/small/wypopover_borderwidth.png "borderWidth: 6")

##### Corner radius & View content insets

![](https://raw.github.com/nicolaschengdev/WYPopoverController/master/screenshots/appearance/small/wypopover_outercornerradius_0.png "outerCornerRadius: 0") , ![](https://raw.github.com/nicolaschengdev/WYPopoverController/master/screenshots/appearance/small/wypopover_innercornerradius_14.png "innerCornerRadius: 14") , ![](https://raw.github.com/nicolaschengdev/WYPopoverController/master/screenshots/appearance/small/wypopover_viewcontentinsets_4-4-4-4.png "viewContentInsets: {4, 4, 4, 4}")

##### Stroke & Fill

![](https://raw.github.com/nicolaschengdev/WYPopoverController/master/screenshots/appearance/small/wypopover_strokecolor.png "strokeColor: #c3045e") , ![](https://raw.github.com/nicolaschengdev/WYPopoverController/master/screenshots/appearance/small/wypopover_filltopcolor.png "fillTopColor: #c3045e") , ![](https://raw.github.com/nicolaschengdev/WYPopoverController/master/screenshots/appearance/small/wypopover_fillbottomcolor.png "fillBottomColor: #c3045e")

##### Gloss

![](https://raw.github.com/nicolaschengdev/WYPopoverController/master/screenshots/appearance/small/wypopover_glossshadowcolor.png "glossShadowColor: #c3045e, glossShadowOffset: {0, 1.5}, glossShadowBlurRadius: 0") , ![](https://raw.github.com/nicolaschengdev/WYPopoverController/master/screenshots/appearance/small/wypopover_glossshadowblurradius_2.png "glossShadowColor: #c3045e, glossShadowOffset: {0, 1.5}, glossShadowBlurRadius: 2") , ![](https://raw.github.com/nicolaschengdev/WYPopoverController/master/screenshots/appearance/small/wypopover_glossshadowoffset_0-3.png "glossShadowColor: #c3045e, glossShadowOffset: {0, 3}, glossShadowBlurRadius: 0")

##### Outer

![](https://raw.github.com/nicolaschengdev/WYPopoverController/master/screenshots/appearance/small/wypopover_outershadowcolor.png "outerShadowColor: #c3045e, outerShadowOffset: {0, 2}, outerShadowBlurRadius: 8") , ![](https://raw.github.com/nicolaschengdev/WYPopoverController/master/screenshots/appearance/small/wypopover_outershadowblurradius_2.png "outerShadowColor: #c3045e, outerShadowOffset: {0, 2}, outerShadowBlurRadius: 2") , ![](https://raw.github.com/nicolaschengdev/WYPopoverController/master/screenshots/appearance/small/wypopover_outershadowoffset_0--2.png "outerShadowColor: #c3045e, outerShadowOffset: {0, -2}, outerShadowBlurRadius: 2")

##### Inner

![](https://raw.github.com/nicolaschengdev/WYPopoverController/master/screenshots/appearance/small/wypopover_innershadowcolor.png "innerShadowColor: #c3045e, innerShadowOffset: {0, 1}, innerShadowBlurRadius: 2") , ![](https://raw.github.com/nicolaschengdev/WYPopoverController/master/screenshots/appearance/small/wypopover_innershadowoffset_0--1.png "innerShadowColor: #c3045e, innerShadowOffset: {0, -1}, innerShadowBlurRadius: 2") , ![](https://raw.github.com/nicolaschengdev/WYPopoverController/master/screenshots/appearance/small/wypopover_innershadowblurradius_0.png "innerShadowColor: #c3045e, innerShadowOffset: {0, 1}, innerShadowBlurRadius: 0")

### Works like UIPopoverController

---

* passthroughViews
* wantsDefaultContentAppearance
* popoverLayoutMargins

### ARC

---

WYPopoverController uses ARC.

### Installation

---

Add this line `pod 'WYPopoverController', '~> 0.1.2'` to your PodFile or add manually these 4 files `WYPopoverController.h`, `WYPopoverController.m`, `WYStoryboardPopoverSegue.h`, `WYStoryboardPopoverSegue.m` and add `Quartzcore` framework to your project.

### Examples

---

##### Simple

```objective-c
WYPopoverController* popoverController = [[WYPopoverController alloc] initWithContentViewController:controller];
popoverController.delegate = self;
[popoverController presentPopoverFromRect:button.bounds inView:button permittedArrowDirections:WYPopoverArrowDirectionAny animated:YES];
```

##### Appearance (Tint Color)

```objective-c
WYPopoverBackgroundView* appearance = [WYPopoverBackgroundView appearance];
[appearance setTintColor:[UIColor orangeColor]];
```

##### Appearance (Flat Popover)

```objective-c
WYPopoverBackgroundView* appearance = [WYPopoverBackgroundView appearance];
        
[appearance setOuterCornerRadius:4];
[appearance setOuterShadowBlurRadius:0];
[appearance setOuterShadowColor:[UIColor clearColor]];
[appearance setOuterShadowOffset:CGSizeMake(0, 0)];
        
[appearance setGlossShadowColor:[UIColor clearColor]];
[appearance setGlossShadowOffset:CGSizeMake(0, 0)];
        
[appearance setBorderWidth:8];
[appearance setArrowHeight:10];
[appearance setArrowBase:20];
        
[appearance setInnerCornerRadius:4];
[appearance setInnerShadowBlurRadius:0];
[appearance setInnerShadowColor:[UIColor clearColor]];
[appearance setInnerShadowOffset:CGSizeMake(0, 0)];
        
UIColor* greenColor = [UIColor colorWithRed:26.f/255.f green:188.f/255.f blue:156.f/255.f alpha:1];
        
[appearance setFillTopColor:greenColor];
[appearance setFillBottomColor:greenColor];
[appearance setStrokeColor:greenColor];
        
UINavigationBar* appearance2 = [UINavigationBar appearanceWhenContainedIn:[UINavigationController class], nil];
[appearance2 setTitleTextAttributes:@{
                  UITextAttributeTextColor : [UIColor whiteColor],
             UITextAttributeTextShadowColor: [UIColor clearColor],
            UITextAttributeTextShadowOffset: [NSValue valueWithUIOffset:UIOffsetMake(0, -1)]}];
```

##### Storyboard

```objective-c
- (void)prepareForSegue:(UIStoryboardSegue *)segue sender:(id)sender
{
	if ([segue.identifier isEqualToString:@"[YOUR_SEGUE_IDENTIFIER]"])
	{
		WYStoryboardPopoverSegue* popoverSegue = (WYStoryboardPopoverSegue*)segue;
        popoverController = [popoverSegue popoverControllerWithSender:sender permittedArrowDirections:WYPopoverArrowDirectionAny animated:YES];
        popoverController.delegate = self;
	}
}
```

### Handling popover controllers during orientation changes

---

When showing a popover controller, there are times when you will need to handle how the popover controller appears after a change in device orientation.

Situations when handling is required:

* If the popover controller is presented from a target rectangle using the `-presentPopoverFromRect:inView:permittedArrowDirections:animated` method of WYPopoverController.
* If the popover controller is presented from a bar button item that is removed after the rotation has finished.

### Change logs

---

A brief summary of each WYPopoverController release can be found on the [wiki](https://github.com/nicolaschengdev/WYPopoverController/wiki/Change-logs).

### Contact

---

* [@mikl_jeo](https://twitter.com/mikl_jeo) on Twitter
* [@nicolaschengdev](https://github.com/nicolaschengdev) on Github
* <a href="mailTo:nicolas.cheng.dev@gmail.com">nicolas.cheng.dev [at] gmail [dot] com</a>

### License

---

WYPopoverController is available under the MIT license.

Copyright © 2013 Nicolas CHENG

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
