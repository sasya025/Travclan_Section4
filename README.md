
# Travclan_Section4

## Holiday-Proximity Demand Tagger

- Pulls India's 2024 public holidays from the Nager Date API.
- Tags bookings whose check-in date falls within ±2 days of a holiday.
- Compares booking value, stay length, and cancellation behaviour.
- Uses date-window matching to classify holiday-adjacent bookings.
- Limitation: only national public holidays are considered.
- Local events and regional festivals are not included.
