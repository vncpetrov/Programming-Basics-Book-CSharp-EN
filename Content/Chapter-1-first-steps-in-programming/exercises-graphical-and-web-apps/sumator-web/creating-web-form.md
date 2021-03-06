#### Create a web form

We find the file **`Views\Home\Index.cshtml`**. **The view (View) of the home page** of our web application is in it:

![](/assets/chapter-1-images/08.Numbers-sum-web-04.png)

We delete the old code from **the file `Index.cshtml`** and write the following code: 

![](/assets/chapter-1-images/08.Numbers-sum-web-05.png)

This code **creates a web form with three text boxes and a button in it**. Inside the fields, values are being loaded, which are calculated previously in the object **`ViewBag`**. It is said that with the click of the button [**Calculate**] the action **`/home/calculate` (action `calculate` from the `home` controller)** will be called.

Here is how **the file `Index.cshtml`** is supposed to look after the change:

![](/assets/chapter-1-images/08.Numbers-sum-web-06.png)