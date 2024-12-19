# TailwindCSS Hover Class Issue

This repository demonstrates a problem where a Tailwind CSS hover class does not apply correctly.  The expected behavior is that hovering over the div changes the background color. However, this does not occur.

## Bug

The `hover:bg-blue-700` class is added but doesn't seem to have any effect. The issue persists even after restarting the development server and ensuring no conflicting styles exist.

## Solution

The solution involves verifying that there are no conflicting styles, and adding `!important` flag to the `hover` class.  This forces the Tailwind class to take precedence over any conflicting styles.

## Setup

1. Clone this repository.
2. Run `npm install`.
3. Run `npm start` (assumes a development server is in place; adjust as needed for your project).