# Simple-LPU-website-frontend
A simple frontend sample of LPU website
This is a single HTML file that creates a basic, styled landing page for the "Lovely Professional University," with all CSS embedded in the document head. It is a full-page static site structure designed for showcasing information and collecting application details.

## Code Structure and Components
The page adheres to a standard web layout:

HTML (Structure): Defines the semantic layout using <header>, <nav>, <main>, and <footer> tags. It includes placeholders for two images (lpu.jpg and lpu campus.jpg) expected to be in a local Resources folder.

CSS (Styling): All visual rules are written within the <style> block.

## Header and Navigation
The header combines a logo/image and the university name (<h1>) using Flexbox (.logoarea) for side-by-side alignment.

The navigation bar (<nav>) is styled with a prominent orange background (rgb(240, 148, 9)).

Navigation links are centered horizontally using Flexbox and feature dynamic hover, visited, and active states that change font size and color dramatically.

## Main Content and Form
The <main> area is divided into two sections:

Campus Image (.intro): Displays the main campus picture, centered on the page.

Application Form (.form): This is the core interactive element.

It is heavily centered using large margin-left: 500px and margin-right: 500px.

Form inputs are stylized with no side/top borders, only a 2-pixel solid orange line at the bottom.

The submit button (#submit) is a full-width orange button that darkens on hover.

## Footer
The <footer> uses a dark gray background (dimgray) and centers the copyright and policy links horizontally using Flexbox.
