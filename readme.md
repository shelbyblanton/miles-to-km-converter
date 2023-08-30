# Miles to Kilometers Converter

## **[100 Days of Code: The Complete Python Pro Bootcamp for 2023](https://www.udemy.com/course/100-days-of-code/)**

By Dr. Angela Yu

*Day 27 of 100:* Tkinter, *args, **kwargs, and Creating GUI Programs

## Project Specs

Using **[TkInter](https://docs.python.org/3/library/tkinter.html)**, develop an application that converts miles to kilometers.

This application is written with Python 3.11.

![alt text](https://github-readme.s3.us-west-1.amazonaws.com/MilesToKm.png)

### Main Features
The application displays two interactive pieces:
- A form input box where a user will enter the number of miles they want converted to kilometers
- A `Calculate` button that triggers the conversion and outputs the kilometers.

## Usage & Requirements

This project uses one library:
- TkInter

### Workflow
Tkinter is used to create a Graphic User Interface (GUI) with a width of 250 pixels and a height of 120 pixels: 

```
window = Tk()
window.title("Mile to Km Converter")
window.minsize(width=250, height=120)
window.config(padx=20, pady=20)
```

Then we add the miles form input to the interface:

```angular2html
# Miles input
miles = Entry(width=8, justify="center")
miles.grid(column=1, row=0)
```

We use Tkinter's `label` functionality to add all of our text to the interface:

```angular2html
# create label
label = Label(text="Miles", font=("Arial", 14))
label.grid(column=2, row=0)

# Is equal to label
iet_label = Label(text="is equal to", font=("Arial", 14))
iet_label.grid(column=0, row=1)

# Result label
res_label = Label(text="0", font=("Arial", 14))
res_label.grid(column=1, row=1)

# KM label
km_label = Label(text="Km", font=("Arial", 14))
km_label.grid(column=2, row=1)
```

And then we add the `calculate` button that will trigger the conversion:
```angular2html
# Calculate button
button = Button(text="Calculate", command=calculate)
button.grid(column=1, row=2)
```

# Getting Started

All of the commands below should be typed into the Python terminal of your IDE (I use PyCharm for my Python Development).

First, clone the repository from Github and switch to the new directory:

    $ git clone git@github.com:shelbyblanton/miles-to-km-converter.git
    
Then open the project in PyCharm.

**Setup is complete!** 

Click Run in PyCharm to see the app in action.


# Author & Credits

Programmed by **[M. Shelby Blanton](https://www.linkedin.com/in/shelbyblanton/)** under the instructional guidance of **[Dr. Angela Yu](https://www.udemy.com/user/4b4368a3-b5c8-4529-aa65-2056ec31f37e/)** via **[Udemy.com](udemy.com)**.
