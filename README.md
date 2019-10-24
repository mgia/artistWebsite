# Sukari Exhibition Website

This project was a last-minute commission website for I Nyoman Sukari Posthumous Artist Exhibition held in Yogyakarta, Indonesia, from 26 July 2019 to 12 August 2019 in conjunction with ARTJOG, the largest contemporary art fair in Java, Indonesia.

The [website](https://sukari.sarasvati.co.id/) was successfully designed, built, deployed, and improved in 10 hours.

## Design

### Concept: 'Appreciate First'

I Nyoman Sukari was one of the most prolific artists in Indonesia, famous for his paintings of ominous, dark yet vibrant energy. From a young age, Sukari has captivated the hearts of art curators, including the richest man in Indonesia at the time. With the character of a true artist, during an exhibition, when the tycoon asked for his painting's price, he responded only with two words that left the tycoon in absolute surprise and subsequent admiration, 'Appreciasi Dulu'.

Based on this story, I attempted to capture the essence of Sukari with the opening screen as a carousel of art pieces instead of the typical home screen, with the caption, 'Appreciate First'. The user is led to view the carousel before subsequently scrolling downwards for the full website.

### Engineering

The website is built to be extremely lightweight with considerations for tight deadlines and slower networks encountered in the location of the exhibition. As a result, only one external library was used and all other aspects were built in-house, as well as image compression.

### Features

- Mobile First Build: Viewport optimized for mobile, responsive for web
- Sticky Footer: Footer bar to constantly show exhibition details with clickable location address and social links
- Dual Language: Two versions created for English / Indonesia mixed audiences

## Usage

### Pre-requisites

To run website on your local machine, ensure that you have node environment installed, and install the following package via npm:

```
npm install -g http-server
```

### Getting Started

In the file directory, run `http-server` to see the following logs:

```
Marcs-MacBook-Pro:sukari marc$ http-server
Starting up http-server, serving ./
Available on:
  http://127.0.0.1:8080
  http://192.168.48.128:8080
Hit CTRL-C to stop the server
```

Copy the URL link into your preferred browser (mine is Google Chrome) to view live local website.

## Built With

To keep the website development lean and account for slower network in Yogyakarta area, this project was built with minimal tools:

- [Bootstrap](https://getbootstrap.com/) - CSS Library used
- [Google Fonts](https://fonts.google.com/) - Font Library

## Acknowledgements

I would like to thank Denis, Oka, Pipin and the Sukari team for helping with copywriting, acquiring image assets and language translation, which allowed the website to be built successfully and in time for the grand opening.

Lastly, I would like to thank Sarasvati Art Management for organizing the exhibition and bringing the magic of Sukari to the world.
