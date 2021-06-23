# Favourite Places - with map EDIT HERE

<a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-nd/4.0/88x31.png" /></a>

> This is part of Academy's [technical curriculum for **The Mark**](https://github.com/WeAreAcademy/curriculum-mark). All parts of that curriculum, including this project, are licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/">Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License</a>.

This project builds on the following two prior projects:

- [Favourite Places](https://github.com/WeAreAcademy/mark-react-proj--favourite-places)
- [Using map](https://github.com/WeAreAcademy/mark-react-basics-proj--using-map)

This repo doesn't need to be cloned. Continue the work on your previous Favourite Places repo.

## Learning outcomes

- Refactor a component to use `.map`

## Refactoring

> 🎯 **Success criterion:** You have refactored your `App` component to use `.map`, and have no duplicated TSX code.

At the end of the _Favourite Places_ exercise, your `App` component is rendering at least 4 instances of the `Place` component, with a lot of repetition in the TSX code.

We can make the code cleaner by using a loop, specifically a `.map`:

1. Extract out the data from the props into an array of objects, each representing the data about one place (ideally, typed using a common `interface`)
2. `.map` over this array to return an instance of the `Place` component for each element
3. Ensure there are no errors or warnings in the console or server logs

## Optional bonus: share favourite places

> 🎯 **Success criterion:** You have deployed an app which presents the entire cohort's favourite places.

1. Agree with the other scholars upon a common interface for the favourite places data.
2. Collate everyone's favourite places data into one large array of objects
3. Consider adding a new property to each place, to indicate _whose_ favourite place it is
4. Deploy to Netlify an instance of the app which uses this collated superset of data
