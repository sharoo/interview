# Level 1

## Goal

The goal is to calculate the price of a vehicle depending on the duration and the amount of kilometers.

## Explanation

You find in `data.json` the pricings for vehicles. Use the `data.json` together with `input.json` to generate `output.json`. Your code should be found in `main.rb`.

## Calculations

To get the proper price all full weeks should be calculated with the weekly price. The remaining full days with the daily price, the remaining hours with the hourly price.

When calculating the prices you should consider if it wouldn't be cheaper to take the daily or weekly price instead.
