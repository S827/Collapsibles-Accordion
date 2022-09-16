# Collapsibles-Accordion
how to make collapsibles-accordion


Add HTML:
Add button element with class name "accordion"
Add div element with class name "panel"
Add some paragraphs

Add CSS:
style the buttons that are used to open and close accordion panel
    bg color
    width
    color
    cursor
    padding
    text-align
    border
    outline
    transition
add bg color when button is clicked or active
    bg color
add style to panel which will be opened or closed
    padding
    bg color
    display as none
    overflow as hidden

Add script
    initialize a var with value of class "accordion"
    declare i
    initialize a for loop to loop through all the buttons with the class name accordion
    add a evenlistener, so that whenver a button is clicked, content will be shown or closed
    so when button is clicked, make accordion classList active
    initialize a var and give the value of the div element which is the child of the button which was clicked
    and check if panel style display is block or not, if yes, make it none else make it block to make it visible or invisible.