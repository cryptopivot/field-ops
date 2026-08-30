# field-ops

Field notes for installing and servicing kiosks, ATMs, parcel lockers, and related hardware.

Written from Field Pivot jobs. Not a vendor manual and not a copy of anyone else's wiki.

Redbox hardware documentation that already exists belongs to [unredbox/Wiki](https://github.com/unredbox/Wiki) and [redbox.wiki](https://redbox.wiki). Use that. This repo is for *how we hang and service machines in the field*.

## What belongs here

- Site survey: power, data, pad/floor, indoor vs outdoor, landlord constraints
- Install sequence for machine types we actually set
- Recurring failure modes in our words, with the printable part linked if we made one
- Jig notes that live better next to a photo than in a CAD file

## What does not

- Client names, store numbers, addresses, keys, credentials
- Copied wiki pages
- Payment-system internals or anything that helps misuse a live machine

## Layout

```
field-ops/
  survey.md          # site survey checklist (starter)
  install.md         # install sequence (starter)
  notes/             # one note per job type or machine family, no site IDs
```

Fill these in from the truck, not from memory of what a manual should say.

Related: [parts](https://github.com/cryptopivot/parts) · [Field Pivot](https://fieldpivot.com)
