# Upper Room Student Fellowship Flyer

A dynamic HTML flyer template that displays student fellowship meeting information pulled from a Google Sheet.

## Files

- `student-fellowship-flyer.html` - Main flyer template

## Setup

1. Create a Google Sheet with two tabs: **Meeting** and **Schedule**
2. Get your sheet ID from the URL: `https://docs.google.com/spreadsheets/d/YOUR_SHEET_ID/edit`
3. Open `student-fellowship-flyer.html` and replace `YOUR_GOOGLE_SHEET_ID_HERE` with your sheet ID
4. Share the sheet as "Anyone with the link → Viewer"
5. Open the HTML file in your browser

## Google Sheet Structure

### Meeting Tab
Key-value pairs with the following fields:
- `church` - Church name
- `group` - Group name
- `date` - Meeting date
- `time` - Meeting time
- `location` - Meeting location
- `topic` - Weekly discussion topic
- `topicSubtitle` - Topic subtitle
- `topicDesc` - Topic description
- `contact` - Contact person name
- `contactEmail` - Contact email address

### Schedule Tab
Rows with the following columns:
- `Time` - Activity start time
- `Label` - Activity name
- `Description` - Activity description
- `Leader` - (Optional) Session leader name
