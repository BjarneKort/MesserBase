# MesserBase
Citizen science project to create a database of Late Medieval Personal Defence Weapons known as Messer. From Bauernwehr to Kriegsmesser. - still under construction

## Information sections

The expandable sections above the filters are defined in `index.html`. Replace
the placeholder text inside each `.info-content` with the desired text or
images. Their buttons appear in a row on wider screens and wrap on smaller
screens. Sections open below the buttons, independently of one another, and
stay open while visitors filter objects.

## Dates

`dateearliest` and `datelatest` are inclusive integer year bounds, displayed
together as **Date**. Use `null` for both when a source does not specify a
defensible range; the displayed date will be `Unknown`. Century-only dates are
represented as 1401-1500 for the 15th century and 1501-1600 for the 16th.

The date slider spans 1350-1650. When narrowed, it includes objects whose
known bounds overlap the selected range, including its endpoints. Objects with
unknown bounds are omitted while narrowed; selecting the full slider range
shows all dates, including unknown dates.

## Regional origin

Set `regionalorigin` in `database.json` to one of the values below. Use
`Unknown` when the origin is not known; current location does not establish
where an object originated. The regional origin filter shows only values
present in the database.

- Unknown
- Austria
- Baltic states (Estonian, Latvian, Lithuanian)
- Balkans (East: Slovenian, Croatian, Bosnian/Herzegovinan)
- Balkans (West: Serbia, Bulgaria)
- Czechia, Slovakia, Bohemia
- France
- Germany (Northern, Danish)
- Germany (Southern)
- Hungary
- Low Countries (Netherlands/Belgium/Flemish/Burgundy)
- Poland
- Romania
- Scandinavia (Norway, Sweden, Iceland)
- Switzerland/Tyrol
- Ukraine, Moldova
