##  EXPENSE TRACKER APP
 ### class - 102. Using list inside of lists

  using ListView.builder to create an lazy list, or better saying, a list that knows exactly how much space it must take because of the itemcount property, after that, used it inside an expand widget, just to give an extra space

 ### class - 103. Creating a custom list item with the card and spacer widgets

  separating the expense item into a widget file, creating a new widget where is used a card widget, wich is a flutter material component or widget, we can say that, and passed as his child, a padding that gives a space between the content and the widget's border, after a column where is passed to as children a text widget where has as value the expense title, followed by a row, that takes the expense amout and used the .toStringAsFixed() method, that can generate a fixed number of character after the comma, a icon, using the Icon class, passed an Icons.alarm, and at last the  expense's date
