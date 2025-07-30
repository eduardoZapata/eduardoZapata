## Hi there 👋

<!--
**eduardoZapata/eduardoZapata** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

## Frontend Portfolio:
### Asana:
_Note: All inputs were implemented to meet WCAG 2.1 AA accessibility standards_

**Rollup number input:**
Input for Asana number field where users can simultaneously view multiple values within one cell.
The unhovered value is the "rollup" value which the value of the current cell + it's children (the subtasks).
On hover, the rollup value moves to the left hand side, and the true value of the cell appears and is editable.
On expansion, the cell input changes to the default number input cell.

https://github.com/user-attachments/assets/62ce43a9-fe1a-4a73-a421-ebba2bf279f9


**Formula editor:**
Created using [Codemirror](https://codemirror.net/) and [JSEP](https://ericsmekens.github.io/jsep/).
This is a text editor like feature where users can create Formulas from their custom Number or Date fields within a project. Codemirror provides the base text editor functionality while JSEP provides parsing and formula validation. Custom styling was added through the plugins in order to render components from the Component Library. External packages were lazy loaded to preserve original bundle size.

https://github.com/user-attachments/assets/2a76f385-2a46-46d4-9fce-0e9c93624d0e



**Multi-enum input:**
Input for Asana multi enum fields where users can select one or more values from a list, and then have them appear within the cell. Users can use mouse or keyboard to select items from the list. They can also use text search to find their item. This input can support users who add up to ~1000 options and render them in a performant manner.

https://github.com/user-attachments/assets/908c9d7e-10ca-4c46-964f-82b80d831850


### Oscar Health:
_Unfortunately screenshots are unavailable for the following features :(_

**Video chat client for Telemedicine feature:**
Built and released initial version of a video chat client which allowed users to call their doctor. Built with React Native and used the [Opentok](https://github.com/opentok/opentok-react-native) sdk

**Mobile survey renderer**
Built dynamic intake survey renderer which ingested structured data, handled form input, and rendered UI components for various form field types (text, checkboxes, dropdowns, etc). This allowed product managers to create and release new surveys on mobile to users using telemedicine without writing any code. Built with React Native




