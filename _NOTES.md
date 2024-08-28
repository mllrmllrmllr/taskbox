# Notes

# Tasks
* `yarn storybook` (Start the component explorer on port 6006)
* `yarn dev` (Run the frontend app proper on port 5173)

# Tutorial
* Vorlage: https://storybook.js.org/tutorials/intro-to-storybook/react/en/get-started/
* Stand: https://storybook.js.org/tutorials/intro-to-storybook/react/en/simple-component/

# Notes – Storybook

## Actions
[Actions](https://storybook.js.org/docs/essentials/actions) help you verify interactions when building UI components in isolation. Oftentimes you won't have access to the functions and state you have in context of the app. Use fn() to stub them in.

## Component Story Format 3 CSF3
To define our stories, we'll use Component Story Format 3 (also known as [CSF3](https://storybook.js.org/docs/api/csf) ) to build out each of our test cases. This format is designed to build out each of our test cases in a concise way. By exporting an object containing each component state, we can define our tests more intuitively and author and reuse stories more efficiently.

# Notes - General

## Component-Driven Development (CDD)
[Component-Driven Development](https://www.componentdriven.org/) (CDD) methodology. It’s a process that builds UIs from the “bottom-up”, starting with components and ending with screens.
