# Lab report 2
## 1. StringServer
I write a a web server called StringServer that show string according to the path we type in, and here is my code.\
![Image](https://github.com/1984Elias42/lab2/blob/main/lab2%201.jpg)
Then I type in the request __/add-message?s=hello__ and here is how result looks like.\
![Image](https://github.com/1984Elias42/lab2/blob/main/lab2%202.jpg)
Then I type in the request __/add-message?s=How are you__ and here is how result looks like.\
![Image](https://github.com/1984Elias42/lab2/blob/main/lab2%203.jpg)
When run these request,\
__First__ I call the main to create the web server.\
__Then__ I called __String handleRequest(URI url)__ in my code. This method works according to the url I type in as the request. I check if there is __/add__ in my path by contains method to add the string. If there is __/add__ in my path then I splite query by __=__ and get the string by get the element in parameters. Then I return that string.
## 2. Bugs
The reverseInPlace method in __ArrayExamples.java__ has bugs. The reason why it can't work properly is because when we go through the for loop, where array was keeping being updated so when we try to operate the old first half of the array, the data inside it is not the original data that we need. That's why this method has a bug. The input we type in which is the array will not casue the problem. To fix this bug, we will creat a deep copy for the input array at first as an reference. And here is my fixed code: 
```
# fixed code
static void reverseInPlace(int[] arr) {
    int[] arrref = new int[arr.length];
    for(int i=0; i<arr.length; i++){
      arrref[i]=arr[i];
    }
    for(int i = 0; i < arr.length; i += 1) {
      arr[i] = arrref[arr.length - i - 1];
    }
  }
```
## 3. Conclusion
Before these 2 labs, I knew nothing about how to create a web server. This is the first time I learn how to create a web server by coding. And learned how to write some codes to do some requests in url. That's the first step for me to do something about the webserver and I think it is very useful.
