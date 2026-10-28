# Café QR ordering + loyalty demo

Live demo: https://sumanthvedala.github.io/cafe-qr-loyalty-demo/

Clickable prototype of a QR table-ordering app with built-in loyalty points.

- **Left:** what a customer sees after scanning the table QR code: menu, cart, phone + OTP login with consent notice, points redemption, payment, live order tracking, rewards and account (download / delete my data).
- **Right:** a simulated version of the café's Petpooja POS, where QR orders would land next to counter and Zomato/Swiggy orders. The real build pushes orders through Petpooja's partner ordering API (credentials come from Petpooja); this screen is a stand-in, not Petpooja's actual UI.

Everything runs in the browser. No data is sent anywhere. Any 10-digit mobile number and any 4-digit code work.

To rebrand, edit the `CAFE`, `RULES` and `MENU` constants at the top of the script in `index.html`.
