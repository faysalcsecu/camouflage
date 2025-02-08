Flutter Dashboard App

This Flutter application demonstrates a simple and visually appealing dashboard layout. It consists of a grid of cards representing various functionalities such as "Customers," "Suppliers," "Products," and more. The app incorporates both icons and images for visualization, providing two variations of the dashboard design.

Features

Dashboard Header: A header area with a green background and rounded corners that displays the app's title ("ONLINE SOFT SELL") and a greeting message ("Hello, Admin").

Grid Layout: A responsive grid view displaying cards for different sections of the app.

Card Design: Each card contains either an icon or an image, along with a title, styled for clarity and usability.

Interactive Cards: Cards are clickable (using InkWell) and designed with rounded corners and elevation for a modern look.

File Structure

main.dart

This is the primary file containing the following components:

Classes

MyApp:

Initializes the application.

Disables the debug banner.

Sets DashboardScreen as the home screen.

DashboardScreen:

The main screen of the application.

Implements a Stack layout to layer the header and content.

Contains a list of dashboard items, each with a title and an associated icon or image.

Uses GridView.builder to create a dynamic grid layout.

DashboardCard:

A reusable widget for each card in the dashboard.

Displays either an icon (first variation) or an image (second variation) along with a title.

Uses a Card widget for rounded corners and shadow effects.

## Screenshots
## Faysal Bin Alauddin
### Header and Grid Layout
![Header and Grid Layout](screenshorts/abc.png)

