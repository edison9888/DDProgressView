# DDProgressView

DDProgressView is a colorful progressView with a animation writen by `Object-C`.

![](./DDProgress.gif)

## Usage

Copy the `DDProgressView.h` and `DDProgressView.m` file to your project. Call the setProgress...method like this:

```
	DDProgressView *progressView = [[DDProgressView alloc] 
									initWithFrame:(CGRect){0,20,320,1}								  
								  backGroundColor:[UIColor blackColor]];
    [progressView setProgress:0.5 duation:2 animated:YES];
```
##See Also
	DDProgressView writen by `Swift`
- DDProgress: <https://github.com/SanLiangSan/DDProgressView-Swift>

## Author

SanLiangSan:

- Email: <254458886@qq.com>

## License
DDProgressView is available under the MIT license. 