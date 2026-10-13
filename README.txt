AquaRescue Turbidity Dashboard

Files:
- index.html: responsive turbidity dashboard, recommendation logic, demo data, and Web Serial support
- assets/robot-arena.png: illustrative Robot Arena image (not a live feed)

How to use:
1. Extract the ZIP, keeping the assets folder beside index.html.
2. Open index.html in a modern browser to use manual readings and demo buttons.
3. For Arduino USB serial, use current Chrome or Edge. Web Serial typically requires localhost or HTTPS; opening a file directly may not allow serial access.
4. Arduino should send one line per reading, either a number such as 4.2 or JSON such as {"turbidity": 4.2}, at 9600 baud.

Safety:
Turbidity indicates cloudiness only. It cannot prove drinking-water safety. The treatment guidance calls for settling/filtration of cloudy water, retesting, and approved disinfection; never calculate a chlorine dose using turbidity alone.
