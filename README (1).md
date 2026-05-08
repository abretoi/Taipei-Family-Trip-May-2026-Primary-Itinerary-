# Taipei Family Trip Guide — May 2026

Interactive single-page Taipei family itinerary web app.

---

## Latest update: Itinerary overhaul — May 10–16 final schedule

This version replaces the previous draft itinerary with the family's confirmed day-by-day plan for May 10–16, 2026. All 7 days have been updated to reflect actual flight details, confirmed activities, specific restaurant targets, and the final departure flight.

### Updated itinerary summary

| Date | Day | Theme |
|------|-----|-------|
| May 10 · Sun | Arrival | Flight DL0069 arrives 7:55 PM · Hotel check-in ~10:30–11 PM · Convenience store snack run · Bubble tea · Early sleep |
| May 11 · Mon | Xinyi & Mother's Day | Yongkang breakfast · Taipei 101 Mall · Din Tai Fung (queue ticket system) · Xinyi shopping · Pokémon Center · Mother's Day dinner |
| May 12 · Tue | Historic Taipei | CKS Memorial Hall + guard ceremony · 228 Peace Memorial Park · Ximending (Donki, Wan Nian Building, crispy milk donuts) · Longshan Temple · Raohe Night Market · optional Ciyou Temple |
| May 13 · Wed | Jiufen & Shifen | Shifen sky lanterns · Shifen Waterfall · Jiufen Old Street · A-Mei Tea House · sunset · Option A: Mala Hot Pot in Taipei / Option B: Keelung Night Market |
| May 14 · Thu | Beitou & Zhongshan | Spring City Resort hot springs (swimsuit-friendly) · Beitou scenic stops · Zhongshan boutiques & cafés · optional Elephant Mountain · Mala Hot Pot dinner |
| May 15 · Fri | Shopping & Birthday | Taipei Underground Mall · Wufenpu wholesale fashion · Ningxia Night Market · Nathan's mom's birthday dinner (TBD restaurant) |
| May 16 · Sat | Departure | Final Taiwanese breakfast · Hotel checkout · Depart OZ712 at 12:25 PM |

### Key changes from previous version

- **Flight details added**: Arrival DL0069 at 7:55 PM on May 10; departure OZ712 at 12:25 PM on May 16.
- **May 10 arrival night**: Realistic timing (~10:30–11 PM hotel check-in), convenience store run, bubble tea, and early sleep. Ningxia Night Market removed — too late after travel.
- **May 11**: Restructured around Din Tai Fung's **queue ticket system** (go, take a number, explore while waiting). Yongkang Street breakfast added (TP Tea, Oolong Tea Project, Tian Jin Scallion Pancake). Mother's Day dinner anchor confirmed.
- **May 12**: Completely new day — CKS Memorial → Ximending (crispy milk donuts, Donki, Wan Nian Building) → Longshan Temple → Raohe Night Market → optional Ciyou Temple. Replaces previous light shopping day.
- **May 13**: Shifen now included in the day trip (sky lanterns + waterfall), then Jiufen in the afternoon/evening. Two dinner options: Mala Hot Pot (Taipei) or Keelung Miaokou Night Market. Previously excluded Shifen.
- **May 14**: Spring City Resort (swimsuit-friendly hot spring resort) replaces generic Beitou hot spring. Mala Hot Pot dinner added. Optional Elephant Mountain for those who want it.
- **May 15**: Reframed as ultimate shopping day + birthday celebration. Taipei Underground Mall + Wufenpu added. Ningxia Night Market added as auntie-friendly option. Birthday dinner for Nathan's mom.
- **May 16**: Simplified to final breakfast + airport departure (OZ712, 12:25 PM). Previous version had a split departure structure.
- **App subtitle** updated from "May 10–17" to "May 10–16 · Departs OZ712 12:25 PM May 16".

### New SPECIAL_LINKS entries added

The following places were added to the link resolution dictionary for proper Google Maps routing:

- Spring City Resort (Beitou)
- Mala Hot Pot Ximen + Gongguan branches
- Ciyou Temple (Songshan)
- A-Mei Tea House (Jiufen)
- Shifen Old Street + Shifen Waterfall
- Beitou Thermal Valley + Hot Spring Museum + Public Library Branch
- Keelung Miaokou Night Market
- TP Tea, Oolong Tea Project
- Tian Jin Scallion Pancake, Don Don Donki, Rainbow Road, Fuzhou Pepper Bun
- Opera Bar

### Included behavior (unchanged from previous versions)

- Explore tab card title links open a Google Maps search for the exact place/activity.
- Explore **Open map** buttons point directly to Google Maps.
- Elephant Mountain resolves to Xiangshan Trail / Elephant Mountain in Taipei.
- No embedded Google Maps API key — all links are standard Google Maps search URLs.
- Drag-and-drop itinerary behavior, insert-between drop lines, replacement behavior, automatic time reflow, and mobile-optimized layout remain intact.

---

## Deployment

Upload `index.html` to GitHub Pages, Firebase Hosting, Netlify, Vercel, or any static host. The root file must remain named `index.html`.

The app is fully self-contained — no external dependencies, no build step, no server required.
