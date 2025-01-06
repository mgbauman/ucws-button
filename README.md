# UCWS Button Component

A reusable icon button component built with Lit. Matthew Bauman experiment.

## Installation

```bash
npm install ucws-button
```
## Usage
Import the component into your project:

```
import 'ucws-button';
```
Then use it in your HTML:
```
<ucws-button type="default">Submit</ucws-button>
<ucws-button type="ghost">Cancel</ucws-button>
```
For development, the `ucws-component-wrapper` component is included. 
Run `npm start` to open a page with the wrapper and edit `index.html` to adjust 
to your local testing and development needs. 

## Properties
`button-type:` Defines the button type (default or ghost).
`href:` Defines the href of the button.
### Slots:
`Default slot:` Used for the button text.
