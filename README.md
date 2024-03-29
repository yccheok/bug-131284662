In API 28, `EditText` will yield incorrect line spacing behavior, when dealing with non-English Unicode. 

Same problem occurs regardless on whether you are using `androidx.appcompat.widget.AppCompatEditText` or `android.widget.EditText`

Please see the following screenshot for API 28. 4th line is being "pushed down" by 3rd line which contains non-English Unicode.

# API 28

![](https://github.com/yccheok/bug-131284662/blob/master/API28.png)

# API 27

Please note that, this problem doesn't occur in API 27. The following is the screenshot for API 27.

![](https://github.com/yccheok/bug-131284662/blob/master/API27.png)
