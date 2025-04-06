*FORMERLY HAYMISHES SAND FARM


Full days journey from [[Cradle]].
First mission to go here

Near [[Good Knight's Rest]]

Has a creepy cellar under the office. In the cellar we find a note that reads:

##### [[Basement Note]]
```dataviewjs
async function getParagraph(pageName) {
    let page = dv.page(pageName);
    if (!page) {
        dv.paragraph("Page not found.");
        return;
    }

    let file = app.vault.getAbstractFileByPath(page.file.path);
    if (!file) {
        dv.paragraph("File not found.");
        return;
    }

    let content = await app.vault.read(file);
    let paragraphs = content.split(/\n\s*\n/); // Split by empty lines

    dv.paragraph(paragraphs.length > 0 ? paragraphs[0] : "No content found.");
}

getParagraph("Basement Note"); // Replace with the actual page name

```



### Mission
Burt Sanddigger, random hand found? [[Session 3]]

Located in [[Jackalope Valley (Region)]]