# Specialty Coffee Calculator

This repository contains utilities to help calculate coffee brewing ratios. Use the provided brew method profiles to quickly configure your preferred brewing process.

## Brew Profiles

Sample profiles are available in the `examples/` directory. Profiles can be written in JSON or YAML format. Below are examples:

- `examples/espresso.json`
- `examples/pour-over.yaml`

These files describe parameters such as the coffee-to-water ratio, brew time, and temperature.

## Using Profiles

The calculator can read a profile file and apply its parameters to compute the amount of coffee and water needed. Run the calculator with the path to a profile file to load its settings.

```
python calculator.py --profile examples/espresso.json
```

Replace the path with any profile you wish to use.


