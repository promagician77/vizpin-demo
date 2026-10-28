# MSRP Only

One static page, no build step, no dependencies.

A working model of the quoting tool described in VIZpin's brief.

1. **Quote** - the internal screen, partner cost and MSRP side by side, with
   quantity breaks, finish upcharges, partner tiers and service terms. Real
   VIZpin product names, invented prices.
2. **The leak** - why "partner costs must never appear" is an architecture
   decision rather than a template one, with both designs side by side.
3. **Rules** - everything priced as an admin-editable table.
4. **The workbook** - the spreadsheet inconsistencies to resolve first, with a
   live demonstration of how discount ordering changes every total.
5. **Plan** - five milestones, 175 hours, $7,000 fixed.

All money is handled in integer cents.

## Run

```bash
npm run dev      # http://localhost:3000
```

## Deploy

```bash
vercel --prod
```
