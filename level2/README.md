# Level 2

## Goal

The goal is to calculate the overdue payment needed for a booking depending on the duration.

## Explanation

You find in `data.json` bookings, payments and vehicle pricings. Use the `data.json` together with `input.json` to generate `output.json`. Your code should be found in `main.rb`.

## Calculations

Use your price calculations from level 1. Add a payment of type `overdue` to the booking with the remaining price difference for the actual booking duration defined in `input.json`. A payment is the amount that is charged from a user. Bookings are a representation of a booked vehicle with the duration and payments of it.
