# ELLIS SARDINE Seminars

A webpage showcasing past and upcoming seminars for the ELLIS SARDINE research group focused on Machine Translation.

## Website

Visit the live website at: https://sardine-lab.github.io/ellis-sardine-seminars/

## Features

- **Upcoming Seminars**: Displays all scheduled future seminars
- **Past Seminars**: Archives of previous seminars
- **Automatic Sorting**: Seminars are automatically categorized based on date
- **Responsive Design**: Works on desktop and mobile devices
- **Easy to Update**: Simply edit `seminars.json` to add or modify seminars

## Adding Seminars

To add a new seminar, edit the `seminars.json` file and add a new entry:

```json
{
  "speaker": "Speaker Name",
  "affiliation": "Institution",
  "title": "Talk Title",
  "date": "YYYY-MM-DD",
  "status": "upcoming"
}
```

The webpage will automatically sort seminars into upcoming or past based on the current date.

## Local Development

To test the webpage locally:

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000 in your browser.