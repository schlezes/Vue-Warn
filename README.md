# Vue-Warn
[Vue Warn] property was accessed during render but is not defined on the instance.

In Vue 3, while testing how to bind properties inside an array, my first attempt generated an error.

The error in console log was a "[Vue Warn]": property styleObject was accessed on the render but not defined on the instance.

The screenshot below shows the error in console log and how to correct-it.

![image](https://user-images.githubusercontent.com/89032071/167672205-017ba11e-498b-40d4-8ad2-a11d2fed444f.png) 

The correction to the error requires the path to the styleObject property; in this case, items[0] to select the index for the styleObject.  Then the  dot notation to select the styleObject property list.

The following screenshot shows how the code renders in the browser and below that, the Vue Dev Tools and console log data.

![image](https://user-images.githubusercontent.com/89032071/167676365-c516b5b1-4391-4805-b750-d48c6d9ec0ea.png)


I have included the files.
