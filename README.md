# CSS-Only Expanding Search Bar Animation

This project is a single-file, pure CSS implementation of an animated, expanding search bar. It demonstrates a common UI pattern where a search icon, when clicked, smoothly transitions into a functional input field.

The icon itself cleverly morphs from a "search" icon (magnifying glass) into a "cancel" icon (an "X") using only CSS pseudo-elements and the `:focus` state.

[Animation of the search bar expanding and the icon changing]

## Key Features

  * **Pure CSS & HTML:** The entire component and its animation are built using only HTML and CSS. No JavaScript is required.
  * **Smooth Animation:** Uses `transition` properties to ensure a smooth, 1-second animation for all state changes.
  * **Icon Morphing:** The `::before` and `::after` pseudo-elements are used to draw the magnifying glass and then transform it into an "X" when the input is focused.
  * **State-Driven Logic:** The animation is powered entirely by the `:focus` pseudo-class and the general sibling combinator (`~`), which alters the icon's properties based on the input's focus state.
  * **Self-Contained:** All markup and styling are in a single `index.html` file, making it easy to understand and integrate.

## Installation and Usage

As this is a self-contained static project, there are no complex installation steps.

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/lucttbyte/css-expanding-search-bar.git
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd css-expanding-search-bar
    ```
3.  **Open the file:**
    Simply open the `index.html` file in any modern web browser to see the component in action.

## Technologies Used

  * **HTML5:** For the basic structure, which consists of only an `<input>` element and a `<div>` element.
  * **CSS3:** For all styling, layout, and animation logic.
      * **Transitions:** For the smooth expansion and icon morphing.
      * **Pseudo-elements (`::before`, `::after`):** To create the icons without extra markup.
      * **Pseudo-class (`:focus`):** To trigger the animation state.
      * **Sibling Combinator (`~`):** To select and style the icon `div` when the input is focused.

## Author

  * **Name:** Lucas Bennett 
  * **GitHub:** [lucttbyte](https://www.google.com/search?q=https://github.com/lucttbyte)

## License

This project is licensed under the MIT License.
