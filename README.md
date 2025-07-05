Exercise 3a: Composite Design Pattern
In the lecture I went through a shop discount calculation example. Download the source files from Moodle.
You need to build on top of this by adding a new method compDelivery() that is declared in the updated component (under ‘Lab Material’ section). Think about where this method needs to be implemented. When called, this method
should return 5% of the total value of the item(s) if they can be discounted, or £0 if not.
Use the provided test driver class. The correct output should be as follows:
iPad Air costs 30.0 to deliver.
MacBook costs 42.5 to deliver.
Power Adaptor costs 0.0 to deliver.
Magic Keyboard costs 0.0 to deliver.
Magic Trackpad costs 0.0 to deliver.
Mac accessory pack {Power Adaptor,Magic Keyboard,Magic Trackpad,} collection costs 0.0 to deliver.
MacBook pack {MacBook,Power Adaptor,Magic Keyboard,Magic Trackpad,} collection costs 42.5 to deliver.

Exercise 3b: Decorator Design Pattern
You are given code for cars using the decorator pattern. There is a core component Car and 2 concrete components BasicCar (provided) and LuxuryCar (not provided). Write the code for LuxuryCar.
You are also provided code for a decorator CarDecorator. You need to write code for 2 concrete decorators called AlloyDecorator and CDDecorator. Decorating with the former costs an extra £250, and £150 with the latter.
Finally, you are given a driver class. Its correct output should be as follows:
Polo costs 10000.0 and is a basic car
GolfSport costs 10250.0 and is a basic car + Alloys
GolfBeats costs 10150.0 and is a basic car + CD Player
SuperGolf costs 10400.0 and is a basic car + Alloys + CD Player
BMW costs 50150.0 and is a shinier, faster car than the basic one + CD Player
1
