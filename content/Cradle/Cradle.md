Nestled in the heart of a vast and verdant landscape, surrounded by towering mountains and pristine rivers, Cradle, known as the _**Cradle of the Gods**_, stands as a beacon of both history and hope. Revered by mortals and gods alike, it is a city steeped in legend—a place where mortal ambition meets divine influence. The very foundations of Cradle were said to have been laid by the gods themselves, who once walked among the city's founding champions. To enter its gates is to walk the path of heroes, to tread upon sacred ground blessed by divine hands.

The city is a sprawling metropolis, its stone streets and marble avenues lined with towering spires and grand temples, each one dedicated to the pantheon of gods who shaped the world. The air is always filled with the hum of activity—warrior merchants peddle rare and exotic goods, scholars debate the ancient texts, and young heroes train in the shadow of legendary monuments.

The city’s mighty gates stand at the threshold of greatness, a challenge to any who seek entry. It is said that only those with extraordinary purpose or divine favor are allowed to pass, for Cradle’s threshold is sacred. Many have tried to enter, only to be turned away by the vigilant guards or by the gods themselves. For the citizens of Cradle, this is more than a city; it is a living testament to the gods' influence, and to the heroes whose deeds are immortalized in its hallowed streets.

Within its walls, legends are born, and the stories of those who walk its avenues echo through the halls of time.

* "City of Heroes"
* Vegas Destination for heroes
* Commerce fueled oasis

New York City metropolis, with a more New Orleans aesthetic

# [[Pantheon District]]
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

	let headers = content.match(/^#+\s.+/gm) || [];

    dv.paragraph(paragraphs.length > 0 ? paragraphs[0] : "No content found.");

	if (headers.length > 0) {
		dv.header(2, "Sections:");
		dv.list(headers.map(header => header.replace(/^#+/gm, "")));
	}
}

getParagraph("Pantheon District"); // Replace with the actual page name

```
# [[Miracle Ward]]
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

	let headers = content.match(/^#+\s.+/gm) || [];

    dv.paragraph(paragraphs.length > 0 ? paragraphs[0] : "No content found.");

	if (headers.length > 0) {
		dv.header(2, "Sections:");
		dv.list(headers.map(header => header.replace(/^#+/gm, "")));
	}
}

getParagraph("Miracle Ward"); // Replace with the actual page name

```
# [[Sunmet Quarter]]
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

	let headers = content.match(/^#+\s.+/gm) || [];

    dv.paragraph(paragraphs.length > 0 ? paragraphs[0] : "No content found.");

	if (headers.length > 0) {
		dv.header(2, "Sections:");
		dv.list(headers.map(header => header.replace(/^#+/gm, "")));
	}
}

getParagraph("Sunmet Quarter"); // Replace with the actual page name

```

# [[Under Cradle]]
Get there by undercarriage :)


