# bbedit-md-text-filters
A collection of custom text filters for processing Markdown in BBEdit

## Usage

1. Copy the filters into: ~/Library/Application Support/BBEdit/Text Filters/
2. If a filter doesn’t run, it may be quarantined by macOS.The following Terminal command will remove quarantine from any given file (use the actual File path rather than "/path/to/file"):

`xattr -d com.apple.quarantine /path/to/file`
3. In BBEdit, select Text > Text Filters, then choose your filter from the menu drop down.
