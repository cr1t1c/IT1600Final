# How to create an SVG

## Step 1 

Open any text editor such as 
1. Sublime Text
2. Atom
3. Notepad++ (Windows only)
4. Visual Studio Code
5. TextMate
6. Brackets

## Step 2 

Decide what kind of SVG you would like to create

### Examples could include
1. Circles
2. Rectangles
3. Rounded Squares
4. Stars
5. Logos
6. A combination of any of these
7. Text

## Step 3

Write your code to create a SVG (Writing code may sound intimidating but its quite simple for this purpose)

You will want to start out with your typical html tags such as...

1. !DOCTYPE html
2. html
3. body
4. style if you would like to use internal css
5. head

It should look something like this

    <!DOCTYPE html>
        <html>
            <head>
            </head>
            <body>
            </body>
        </html>

## Step 4

Within the body tags of your code you will want to define a SVG tag

That will look like this

    <!DOCTYPE html>
        <html>
            <head>
            </head>
            <body>
            <svg>
            </svg>
            </body>
        </html>

## Step 5 

Define what you want your svg to look like by adding

1. Width
2. Height
3. x-axis
4. y-axis
5. Stroke
6. Color

That will look like this

    <!DOCTYPE html>
        <html>
            <head>
            </head>
            <body>
            <svg>
        <rect x="0" y="0" width="152" height="152"    rx="20" ry="20" stroke-width="5" stroke="cadetblue" fill="red"></rect>
        <circle cx="76" cy="76" r="75" fill="cadetblue"></circle> 
        <text fill="white" font-size="45" font-family="Sans-serif" x="8" y="86">IT1600</text>
        </svg>
            </body>
        </html>

## Step 6

Look at what you created and tweak it to make it look exactly how you'd like

That will come out to be

![Example](example.png)

Link to examples 

[Examples](examples.md)