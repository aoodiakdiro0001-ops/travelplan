# ✈️ TripPlan — Travel Budget & Itinerary Planner (MIT)

Destination + days + style → daily budget breakdown and day-by-day
itinerary. UI in EN/TR/AR. Static single file + README.

## Data (9 destinations, 2026 estimates)

Istanbul, Dubai, Kuala Lumpur, Paris, Bali, Cappadocia, Antalya, London,
Maldives — per-person daily hotel/food/transport/activity rates across
Budget/Mid/Luxury/Family tiers + real famous attractions per city +
typical RT flight defaults (editable). Round-robin itinerary builder:
light arrival, full middles, rest day on long trips, souvenir departure.

## Money & contact

- `CONFIG.aff` booking links (Booking deep search verified 200,
  Skyscanner, GetYourGuide) with REF badges — paste real affiliate URLs.
- `CONFIG.ads` travel-ad slot.
- Donate: BTC + USDT-TRC20 + IBANs.
- 📧 baranavisat@gmail.com · 📞 +90 531 326 37 22 · WhatsApp

## Run

```bash
cd travelplan
python3 -m http.server 8080
```

## License

MIT. Estimates — verify live prices when booking.
