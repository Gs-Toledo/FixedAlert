# FixedAlert

FixedAlert is a straightforward TypeScript library designed to streamline the process of displaying fixed-top alerts in your web applications. Whether you're dealing with routine front-end tasks or leveraging Bootstrap styles for dynamic alerts, FixedAlert simplifies the implementation for a more seamless experience.

## Why FixedAlert?

Creating dynamic alerts in my front-end projects became a repetitive task, especially when using Bootstrap styles. 
To enhance efficiency and streamline the process, I developed FixedAlert, aiming to simplify the generation of fixed-top alerts and improve the overall developer experience.

## Installation

You can easily integrate FixedAlert into your project using npm. Simply run the following command in your terminal:


```bash

npm install fixed-alert

```

This command will install FixedAlert and allow you to leverage its capabilities for displaying fixed-top alerts with ease.

## How to Use

To use FixedAlert, instantiate the class by providing the message to be displayed and the Bootstrap color class from the following options:

- `primary`
- `secondary`
- `success`
- `danger`
- `warning`
- `info`
- `light`
- `dark`

Here is an example:

```typescript
import FixedAlert from 'fixed-alert';

// Instantiate the FixedAlert class with a message and Bootstrap color class
const alertInstance = new FixedAlert('This is a sample alert message', 'success');
