# Markdown to Google Docs Converter

## Description
This Python project, designed for Google Colab, automates the conversion of Markdown-formatted meeting notes into a professionally formatted Google Doc. It utilizes the Google Docs API to parse specific Markdown syntax (headers, lists, checkboxes) and applies custom styling for mentions (@name) and footer metadata.

## Features
- **Smart Parsing**: Converts Markdown Headers (#, ##, ###) to Google Docs Heading styles.
- **Task Management**: Transforms Markdown checkboxes (`- [ ]`) into interactive Google Docs checklists.
- **Formatting**: Handles nested bullet points and text indentation.
- **Styling**: 
  - Highlights user mentions (e.g., @sarah) in bold blue.
  - Formats footer metadata (recorder, duration) distinctively.
- **Automation**: Creates the document directly in your Google Drive.

## Dependencies
- `google-auth`
- `google-auth-oauthlib`
- `google-auth-httplib2`
- `google-api-python-client`

## Setup & How to Run in Colab

1. **Open Google Colab**: Create a new notebook.
2. **Paste the Code**: Copy the Python script into a code cell.
3. **Run the Cell**: 
   - You will be prompted to authenticate with your Google account. 
   - Allow the notebook access to manage your Google Docs.
4. **Result**: The script will print the link to the newly created Google Doc.

## License
MIT
