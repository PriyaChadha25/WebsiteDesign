Cascading Style Sheets- Day2

INTRO: CSS can be written in either inline styles or external stylesheets. 

-> inline style example:- <img src="ap_8.png" width=200px height=200px style="float: right;  padding: 0px 0px" />
-> external style:- First make style.css page. Then write <link rel="stylesheet" type="text/css" href="style.css"> inside head tag. Thereafter practice the following examples. Make sure the name used inside css file is with a . (dot symbol). The same name used inside index.html page as a class name. 
    
    Example(index.html): <div class="menu"> </div>
    Example(styles.css): .menu {...styles written here....}


1. To create a box with border
div{
   border: 2px solid rgb(8, 30, 226);
   border-radius: 20px;
}

2. To give shadow to the box.
-> First no: 10px (it is used for giving horizontal shadow)
-> Second no: 10px (it is used for giving vertical shadow)
-> Third no: 2px (it is used to give the blur effect)
-> Forth no: color (it is the color of the shadow) 

Example:
div{
box-shadow: 10px 10px 2px rgb(250, 126, 126)
}

3. To give gradient effect to the box:
    (i)
        div.gradient{
        background: radial-gradient(red, rgb(183, 0, 255));
        box-shadow: 10px 10px 2px rgb(250, 126, 126)
        }

    (ii)
        div.gradient{
        background: linear-gradient(top,red, rgb(183, 0, 255));
        box-shadow: 10px 10px 2px rgb(250, 126, 126)
        }

    (iii)
        div.gradient{
        background: linear-gradient(to right,red, rgb(183, 0, 255));
        box-shadow: 10px 10px 2px rgb(250, 126, 126)
        }

    (iv)
        div.gradient{
        background: linear-gradient(to bottom right,red, rgb(183, 0, 255));
        box-shadow: 10px 10px 2px rgb(250, 126, 126)

        }
    

4. To create a box with fixed size.
div.subcontainer{
    width: 70%;
    height: 200px;
    color: red;
    padding: 20px;
}





