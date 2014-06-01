UIImage+ColorFromImage
======================

`UIImage+ColorFromImage` is a category on `UIImage` which returns a `UIColor` based on the image this method is called from.

## Using ColorFromImage

Add the category to your project using [CocoaPods](http://cocoapods.org).

    pod `UIImage+ColorFromImage`

Using the category

    #import <UIImage+ColorFromImage/UIImage+ColorFromImage.h>
    
    UIImage *image = [UIImage imageNamed:@"red"];
    UIColor *redColor = [image sqf_colorFromImage];
