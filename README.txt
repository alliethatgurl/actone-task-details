ActOne Task Details – Excel side panel for the Master Sheet

Files
- taskpane.html  : the panel (Load selected row, Prev/Next, Find Design ID, edit + Save)
- assets/        : ribbon icons
- manifest.template.xml : add-in manifest; replace __BASE__ with the HTTPS folder where the files are hosted

Install (once per person)
1. Host this folder on any HTTPS site (e.g. GitHub Pages).
2. Replace __BASE__ in manifest.template.xml with that address, save as manifest.xml.
3. Excel (web or Mac): Home > Add-ins > More Add-ins > My Add-ins > Upload My Add-in > choose manifest.xml.
4. A "Task Details" button appears on the Home tab under "ActOne".
