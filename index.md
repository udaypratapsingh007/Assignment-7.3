# Assignment 7.3 - Responsive Product Listing

## Layout

The six product cards are inside the .product-list container, which uses Flexbox.

- display: flex puts the cards in a row.
- flex-wrap: wrap lets the cards move to the next line when there is not enough space.
- gap: 20px adds equal space between the cards, both across and down.

## flex-grow, flex-shrink and flex-basis

Each card uses these values:

- flex-basis: 280px is the preferred starting width of the card.
- flex-grow: 1 lets the cards grow to fill the extra space in a row, so there are no empty gaps at the end of a row.
- flex-shrink: 1 lets the cards become smaller if the screen is narrower than the space they need.

On a wide screen three cards fit in a row. As the screen gets narrower, the cards wrap, first to two per row and then to one card per row on a phone.

