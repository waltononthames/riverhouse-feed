# riverhouse-feed

Daily events feed for Riverhouse Barn Arts Centre, Walton-on-Thames,
read by the walton-on-thames.org events refresh at 05:00 UK time.
Written by Atlas each morning by 04:15 Europe/London.

## Files
- events-latest.json: every performance from today onwards, sorted by start time
- changes.json: today's new, changed and removed events
- events-latest.csv: the same events as a spreadsheet
- status.json: written only when a run fails

## Rules
- Only Atlas writes here. Do not edit the files by hand.
- A file with "complete": false is a partial scrape. The site never
  treats a missing event in a partial file as a cancellation.
