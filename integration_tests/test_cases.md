# Integration Test Cases:
- **Preconditions**:
1. The coffee machine is ON.

## Test Case: Water heater and pump integration
- **Description**: Ensure that the water heater and pump work together to deliver hot water at the correct temperature and pressure.
- **Steps**:
  1. Click on the water heating button and wait for one minute.
  2. Place a cup under the pump.
  3. Pump the water using the Pump button.¨
  4. Check the temperature and pressure of the output water.
- **Expected Result**: The temperature is cca 90 degrees Celsius, and the pressure is within the expected range.

## Test Case: Grinder and brew unit integration
- **Description**: Verify that the grinder delivers ground coffee to the brew unit correctly and the brew unit processes it properly.
- **Steps**:
  1. Initialize the grinder and brew unit components.
  2. Grind the coffee beans using the grinder.
  3. Brew the coffee using the brew unit.
  4. Check the output coffee for proper grind and brew quality.
- **Expected Result**: The coffee is correctly ground and brewed according to the settings.

## Test Case: Control panel and functional units integration
- **Description**: Verify that selecting a coffee option on the control panel correctly activates the grinder, heater, and pump in sequence.
- **Steps**:
  1. Initialize the control panel, grinder, water heater, and pump components.
  2. Select a coffee option on the control panel.
  3. Ensure the grinder grinds the coffee beans.
  4. Ensure the water heater heats the water.
  5. Ensure the pump delivers the water.
  6. Check if the final coffee output is what you choose on control panel.
  - **Expected Result**: The components operate in sequence, and the coffee is correctly brewed.