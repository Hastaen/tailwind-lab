# Tailwind CSS Playground

A simple starter project for playing around with [TailwindCSS](https://tailwindcss.com/) in a proper [PostCSS](https://postcss.org/) environment.

1. Install the dependencies:

    `npm install`

2. Start the development server:

    `npm run serve`

    Now you should be able to see the project running at localhost:8080.

If you are using VScode the extension "Tailwind CSS IntelliSense" is highly recommended.

## Mission

In the folder "super-nice-designs" there are some really bad designs. The goal of the workshop is to implement the design/layout shown.

## The rules:

1. You can only use Tailwind classes. No vanila JS!

2. You must override the default colors (You can generate a palette [here](https://mycolor.space). Use the classy palette. All five colors must be used in the final result)

3. The design must not "break" when toggling desktio/mobile. 

4. No text should wrap.

5. Add some kind of placeholder where text is Specified in the design.

## Assignment 

Besides implementing the design these are specifications that must be done.

- Every odd card must have rounded borders.

- TailwindCSS is mobile-first by default. The design for mobile views should be used until 1000px width. (You need to override the default responsive breakpoints)

- Use "Extracting components" when facing duplication issues.

- Every even card should have hover effect where a dotted border is visble.

- The list of contact cards should stack vertically when "mobile". They should stack horizontally with two columns on desktop.

## Tips

[DOCS](https://tailwindcss.com/)

The assigments will have you editing the tailwind.config file.

The follwing core concepts will have information you need

- Responsive design

- Psuedo-class variants

- Extracting components

- Customization