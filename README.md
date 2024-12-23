This project is about creating an automated alert system for IV fluid monitoring to improve patient safety in hospitals. The system uses a weight sensor (load cell) to measure how much fluid is left in an IV bottle. Here's how it works:

Measuring Weight: The load cell checks the bottle's weight and sends this data to an HX711 module, which makes the weight information understandable for a small computer (Arduino).

Real-Time Monitoring: The Arduino keeps track of the fluid level in real-time. If the fluid goes below a certain limit (10% of the full bottle), the system knows the bottle is almost empty.

Alert Mechanism:

When the fluid is low, the system:
Shows a warning on a small screen (LCD display).
Sends a signal through RF wireless communication to another unit.
This unit lights up an LED and activates a small vibration motor, alerting medical staff immediately.
Why It’s Useful: This system removes the need for nurses or doctors to manually check IV bottles all the time. It ensures patients are safe by giving timely warnings when fluid levels are critically low.

In short, it’s a smart, low-cost solution to make IV fluid management more efficient and reliable!
