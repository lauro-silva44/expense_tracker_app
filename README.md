## EXPENSE TRACKER APP

### class - 102. Using list inside of lists

using ListView.builder to create an lazy list, or better saying, a list that knows exactly how much space it must take because of the itemcount property, after that, used it inside an expand widget, just to give an extra space

### class - 103. Creating a custom list item with the card and spacer widgets

separating the expense item into a widget file, creating a new widget where is used a card widget, wich is a flutter material component or widget, we can say that, and passed as his child, a padding that gives a space between the content and the widget's border, after a column where is passed to as children a text widget where has as value the expense title, followed by a row, that takes the expense amout and used the .toStringAsFixed() method, that can generate a fixed number of character after the comma, a icon, using the Icon class, passed an Icons.alarm, and at last the expense's date

### class - 104. Using Icons & Formatting Dates

in the class we createad a map that takes a category and an icon, so the ideia is when we are ate the expense_item widget, we can use the it to pass the category and acessing the list

### class - 105. Setting an AppBar with a Title Actions

in this class was introduced the appbar, and the actions, wich is a list of widget, by default, i guess it is pushed to the right corner

### class - 106. Adding a modal sheet & understand context

insert a modal bottom sheet, where using an context, and knows that flutter provide a universal context, and each widget has its own context

### class - 107. Adding a modal sheet & understand context

using a textField widget to insert text in a new component, NewExpense, passed inside the showBottomModalSheet

### class - 108. Getting User Input on Every Keystroke    

using the onChanged method from the textField to store a the value in a variable by passed a defined function outside the buil method as argument

### class - 109. Letting flutter do the work with textEditing Controller  

using TextEditing controller 