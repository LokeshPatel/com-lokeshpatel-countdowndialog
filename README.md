cordova-plugin-countdowndialog
=============

## Installation
```
cordova plugin add com-lokeshpatel-countdowndialog

```
## Methods
- `CountDownDialog.show`

- `CountDownDialog.hide`

#### Count Down Dialog show default
 ```
     CountDownDialog.show();
```
### Need to custom count down dialog like : Change fontSize,fontColor,increase/decrease time and start form 1/0
```
 var option = {"countTime":"12000",
                "fontSize":"150",
                "fontColor":"#FFF000",
                "isCountStartFormOne":"true"};
 CountDownDialog.show(option);

```
- __countTime__: Set time for count down up to  Optional ._(String)_
- __fontSize__: Set font size Optional. _(String)_
- __fontColor__: Set font color Optional. _(String)_
- __isCountStartFormOne__: Set true/false when start count down form 1/0 : _(String)_

#### CountDownDialog.hide

    CountDownDialog.hide();
    


#Screenshots

<img src="https://dl.dropboxusercontent.com/s/dsyxioyr0znul7u/greenImage0.png?dl=0" alt="Count 0" width="239">
<img src="https://dl.dropboxusercontent.com/s/hi7dd67fritlovl/greenImage1.png?dl=0" alt="Count 1" width="239">
<img src="https://dl.dropboxusercontent.com/s/8y65sbasfcy9xf9/greenImage2.png?dl=0" alt="Count 2" width="239">


