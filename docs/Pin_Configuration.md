# ESP32 Pin Configuration

## LDR Connections

| ESP32 Pin | Sensor |
|-----------|--------|
| GPIO34 | Top Left LDR |
| GPIO35 | Top Right LDR |
| GPIO32 | Bottom Left LDR |
| GPIO33 | Bottom Right LDR |

## Horizontal Motor

| ESP32 | ULN2003 |
|--------|----------|
| GPIO19 | IN1 |
| GPIO18 | IN2 |
| GPIO5 | IN3 |
| GPIO17 | IN4 |

## Vertical Motor

| ESP32 | ULN2003 |
|--------|----------|
| GPIO16 | IN1 |
| GPIO4 | IN2 |
| GPIO2 | IN3 |
| GPIO15 | IN4 |

## Power

- ESP32 powered using USB.
- Both ULN2003 drivers powered by external 5V.
- Common GND between ESP32 and power supply.
