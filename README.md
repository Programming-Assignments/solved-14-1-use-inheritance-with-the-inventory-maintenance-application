Download Link: https://assignmentchef.com/product/solved-14-1-use-inheritance-with-the-inventory-maintenance-application
<br>
<p class="ui header product-top-header" title="Inventory Maintenance application Solution ">In this exercise, you’ll add two classes to the Inventory Maintenance application that

inherit the Invltem class. Then, you’ll add code to the forms to provide for these new

classes.

1.       Open the InventoryMaintenance project in the Extra ExercisesChapter

14InventoryMaintenance directory. review the code for the New Item

form to see that the items in the combo box and the label for the combo box

depend on which radio button is selected.

2.       Display the Invltem Class and modify the GetDisplayText method so it’s

overridable

3.       Add a class named Plant that inherits the Invltem class. This new class should

add a string property named Size. It should also provide a default constructor and

a constructor that accepts four parameters (item number, description, price, and

size) to initialize the class properties. This constructor should call the base class

constructor to initialize the properties defined by that class. Finally, this class

should override the GetDisplayText method to add the size in front of the

description, as in this example:

3245649 1 gallon Agapanthus ($7.95)

4.       Add another class named Supply that inherits the Invltem class and adds a string

property named Manufacturer _ Like the Plant class, the Supply class should

provide a default constructor and a constructor that accepts four parameters, and

it should override the GetDisplayText method so the manufacturer is added in

front of the description like this:

9210584 Ortho snailpellets ($12_95)

Modify the event handler for the Click event of the Save button on New Item

form so it creates a new item of the appropriate type using the data entered by the

user. Test the application by adding at least one of each type of inventory item