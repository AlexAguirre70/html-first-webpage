# HTML CSS Course 2023 - First WebPage

This is the first webpage created to relearn the basics of HTM and review the document structure.<br/>

We will also will review white space collapsing in the editor but the rendering ignores empty spaces. We need to use special html elements to create spacing.<br>

### Lorem Ipsum
We review also how to use emmet to provid text place holder using Lorem Ipsum by typing lorem into the content between element tags. You can limit how many words you want to create by adding the number after the word lorem. Example: lorem50 to get 50 word filled <br/>

### Images
We review the basics on images. Images require attributes of src and alt. The source is the image file location and alt is text in case the image cannot be rendered or for text only browsers and accessibility. We also review relative and absolute paths to src the image file location.<br/>
To use images for commercial or production sites, you will need to use royalty free image from sites like: Pexels, Pixabay or Gratisography <br/>
Now we review the height and width attributes for the img element tag. If we only provide the width tag, then it automatically resizes the height to maintain the image ratios. <br/>
If we uses images that are large, it will slow down the load times. We need to rezise or crop the images prior to loading to improve load speed. <br/>
<br/>
### Comments
To add comments we need to use the "!-- element --" insdie the angle brackets. You can also use the shortcut. CMD+/
<br/>Comments are not displayed on the page<br/>

### External, Internal and Single Page links
To add a link we need to use the a element tag that takes an href attribute that navigates to where you want to send the user. It can also set the target attribute to load the content on a blank new page, or on the existing page.<br/>
To navigate to an section within the same page, we need to add the id attribute to the image and give it a name. Then in the a tag reference that id in the href using the hashtag and name. example: href="#udemy1"<br/><br/>

You also add an empty/dummy link. This is simply a link that does not navigate anywhere. It is simply a placeholder to add the href later. We insert the # for the time being. <br/><br/>

You can also wrap an image or a button rather than text with the a tag. When hovering the mouse pointer over it, it changes the icon to the clickable hand
<br/><br/>

### Other Element Types

#### Sub and Sup
The sub element places any test inside it lower than the normal text. The sup element puts it above
<br/><br/>

#### Strong and em
The strong element changes the text to BOLD that is within the element tags. 
<br> The em element italicized the text in between the tags.
<br/>
These should be used more than just styling. This should be used for accessibility emphasized
<br/>
<br/>
### Special Characters
These can be inserted by preceding the code by the & sign. Example for Copyright we use "&copy" followed by the ";" semicolon. Codes are available for others on the web
<br/>
<br/>
### Unordered and Ordered lists
Unordered list take ul tag and must contain the li (list item) tags in between to create the list. These are primarily used for navigation links. You can assign the list-style-type of bullet to be:
* disc
* circle
* square
* none

<br/>
Ordered require the ol tag and have different type of list-style-types. You can use

* i for lower case roman numerals
* I for upper case roman numerals
* a for lower case letters
* A for upper case letters
* 1 for numbers
<br/><br/>

### Tables
To create a table, we need to use the Table element and requires 3 things
* th - table head
* tr - table row
* td - table column
<br/><br/>

### Forms
Forms are used to collect user information and can be created using the form tag. This tag has 2 primary attributes that forms take:
* action - this is the endpoint url where the data will be sent to
* method - what method to use to send the data
<br/>
Forms also take lables and different types of input fields:
<br>
* text - single line of text
* textarea - more than 1 line of text
* radio buttons - can only select one
* checkboxes - can select more than one
* select - from a list provided

<br/>
the **input fields** also takes an attribute of name. The name represents the key for the data in that field. <br/> 
example: name="firstName", so when data is sent it will be firstName:Alex

<br/>
the input field also can take an id that is associated with the label. These names must match exactly
<br/>
<br/>
The **label** is simply a text element tag to make clear what is supposed to go into the input field. To reference the input field it must take a for attribute that matches the input element id. when clicking on the label it then automatically toggles to the field where to enter that information. Great use for accessibility<br/>
example: label for="firstname" with the input field having id="firstName" <br/>
<br/>
<br/>
Alternatively to using a label, the input field can take an attribute of placeholder that can be used to instruct the user on what is expected in that field. When you start typing inside the field, the placeholder disappears.
<br/>
<br/>
Another input field that can used is the value attribute. whatever we set this to, will automatically appear as the input in that field
<br>
<br>
To add a **textarea** we need to add the textarea element. It takes 2 primary attributes to specify the height and width of the area. cols and rows.
<br>
<br>
To add a **radio** button, we need to use the type radio, and give it a name. With radio buttons, we can only select 1 value. In addition, we need to create 1 input for each option, but it is important that they have the exact same name attribute so that only one choice can be selected. 
<br> We also need to include the **value** attribute, so when the option is selected it can pass that value as data.
<br>
If you want to  have a radio button selected by default you must add the special keyword "checked" to the input tag.
<br>
<br>
To create **checkboxes** we need to use the checkbox type. They are setup the same way radio buttons are, but this input type allows us to select multiple options
<br>
<br>
To use the select input we need to use the select tag and assign it a name attribute. Next, we must setup the options to select by using the option tag. The option tag takes the value attribute that is needed to pass that data when the form is submitted.
<br>
To allow to select multiple options, we must include the keyword "multiple" in the select input tag.
<br>
<br>

The form lastly can take a **submit** element that tells the form to take the action needed for the data in the inputs. <br>
We can use a button or an input with the type attribute as submit. This also takes a value attribute that displays the text to show on the button face.<br>
When clicking the submit button it adds the name and input value in the field an adds it to the action URL provided to send the data.
<br/><br/>



