# index.html

![image](https://github.com/EaswaranPottiK/WeeklyTest4CSSProperties/assets/38095510/705f01d3-3949-454a-a649-19c0b35f0cf5)

!doctype defines that html code is written here

html lang = en specify language used here is english

meta charset defines the encoding used, in this case its utf 8

meta name and content ensure consistancy of view in mobile and desktop

title is the text displayed on tab, here the text written is - Document

html is lined to css via the link tag; href specify the location of doucument and rel specify the relationship - in this case it is stylesheet 

here we also import font from google using link, href and rel

![image](https://github.com/EaswaranPottiK/WeeklyTest4CSSProperties/assets/38095510/d79a7826-4cc7-4100-a9ec-8f40b1dae792)

header tag is used to define fixed nav bar on the top of page - here there is two span defined with class logoText and navBar respectively

these 2 classes takes up eqaul space as per styling rules and anchot tags inside navBar takes up equal spaces of navbar

![image](https://github.com/EaswaranPottiK/WeeklyTest4CSSProperties/assets/38095510/b1e07f4f-0d8d-45b6-8610-58e3ca0dc04a)

class mainContent with div defines page with background image; it consist of a heading, a paragraph and a button each with classes for styling 

![image](https://github.com/EaswaranPottiK/WeeklyTest4CSSProperties/assets/38095510/ef0dcda3-4e75-42b3-8291-ef51ee66d2b2)

div with class name carPage defines my services page: cardPage has a heading tag h1, a paragraph tag p, 6 similar spaced rectangles

Each div with class card consist of an image, h3 tag - heading and a paragraph tha discribe about that card

![image](https://github.com/EaswaranPottiK/WeeklyTest4CSSProperties/assets/38095510/b6483d23-4a71-4654-a159-15d580e21f1b)

div about us class consist of a heading h1 tag, paragarph tag and a div with class readingContent

reading content consist of a heading and multiple span elements. Span is used as it an inline elment so it can be easily aligned 

![image](https://github.com/EaswaranPottiK/WeeklyTest4CSSProperties/assets/38095510/84a93b04-e796-4c51-a942-c9597e9965a8)

an unordered list is used to display name of people and their titles 

![image](https://github.com/EaswaranPottiK/WeeklyTest4CSSProperties/assets/38095510/c77b4fad-5243-434e-8139-ff25d51f19f9)

The last part of page consists of an h1 tag p tag and class named lastTwoClasses; Using flex they are arraned in horizontal manner

lastTwoClasses consist of agin two classes - Left and Right which are arranged horizontally using flex 

# style.css

![image](https://github.com/EaswaranPottiK/WeeklyTest4CSSProperties/assets/38095510/01b6264f-0926-4115-8c70-973dfdcfb54e)

* is the universal selector with padding, margin set to zero to remove all the default spacing property

box sizing : border-box is used ensure page does to exceed the limits set

here iam importing a font - poppins with sans-serif as backup

![image](https://github.com/EaswaranPottiK/WeeklyTest4CSSProperties/assets/38095510/48c0bdc7-2e8c-41cf-baa8-05d269f38d8c)

here background color is specified 

color is the color of text inside the box

cursor pointer is used to change behaviour of mouse pointer when it is on top of an element 

height is specified and with 100% makes use of all the available width

position is fixed to make sure element stays in the position even if i scroll down

along with fixed postion 2 diamention position also needs to be specified 

here flex box is used to space items

z index is used to ensure that there are no elements that will get printed on top of nav bar

![image](https://github.com/EaswaranPottiK/WeeklyTest4CSSProperties/assets/38095510/e39bffe9-bc7d-44d3-8afc-41c8e3c00404)

font weight and font size are used to set the thickness and length of fond

padding- right is used to put a space on RHS

display: inline-block; to used to make block items inline

![image](https://github.com/EaswaranPottiK/WeeklyTest4CSSProperties/assets/38095510/73dc66f6-6e92-410c-a996-6bf42af06d99)

background : url is used to put an image in the screen

background position: center make the image aligned to center

backgroud repeat: no repeat ; suppose there is an image with less size than allocated page, then image will get multipled and printed to avoid this issue this property is used 

flex-direction: coloumn make sure elements are arranged horizontally from top to bottom

![image](https://github.com/EaswaranPottiK/WeeklyTest4CSSProperties/assets/38095510/50d8eaea-50ed-4a07-a71f-9c3df5a47382)

text-shadow is used to achieve a halow effect on the text printed. Text shadow format is x value, y value, speard factor and opacity

![image](https://github.com/EaswaranPottiK/WeeklyTest4CSSProperties/assets/38095510/b8ede975-fd40-45ef-92bf-db4cae717141)

box shadow is used to achieve a halow effect on the rectangle 

border is the outline of the rectangle 

border - radius is used to make rectangle corner rounded 

cursor:pointer is used to manipulate behaviour of mouse on top of the element 

transition is used for animation effect 

when the mouse is on top of button, the background of mouse changes to parent element color and the text color becomes black

![image](https://github.com/EaswaranPottiK/WeeklyTest4CSSProperties/assets/38095510/92560e1a-62dd-4fe0-8afc-c84661ae47ce)

display flex is used to flex box

justify content specify different spacing options in flexbox

flex-wrap: wrap : if the contents exceeds specified length of the page then the contents are placed in next line

![image](https://github.com/EaswaranPottiK/WeeklyTest4CSSProperties/assets/38095510/0d01777f-b1cd-442b-ab09-d7fd91cbabb4)

![image](https://github.com/EaswaranPottiK/WeeklyTest4CSSProperties/assets/38095510/42ed117a-9be4-467e-8f0b-3bb06c514281)

in line 149- ',' is used to apply same styling to mutiple elements 

in line no 157 the styling is only applied to li which is a descended of list class 

![image](https://github.com/EaswaranPottiK/WeeklyTest4CSSProperties/assets/38095510/252a1c56-34d0-4f16-ae8b-bc0bbe763a7f)

border none is used to remove boder of the rectangle in this case button 

The rest of propertys are already explained above




























