`position: sticky` wordt vaak gebruikt voor navigatiebalken of elementen die zichtbaar moeten blijven wanneer de gebruiker naar beneden scrolt op de pagina, maar die moeten terugkeren naar de normale positie wanneer de gebruiker weer omhoog scrolt.

Wanneer een element is ingesteld op `position: sticky`, gedraagt het zich in eerste instantie als `position: relative`.

Dit betekent dat het element op de normale positie in het document wordt weergegeven.

Wanneer het opgegeven scrolpunt is bereikt, schakelt het element over naar een vaste positie (alsof het is ingesteld op `position: fixed`) en scrolt het niet mee met de rest van de inhoud.

Hier is een voorbeeld:

## --- code ---

language: css
filename:
line_numbers: true
line_number_start: 1
line_highlights:
-----------------------------------------------------

.sticky-element {
position: sticky;
top: 50px;
}

\--- /code ---

Regel 2 stelt de positie-eigenschap in op `sticky` voor elk element met het kenmerk `class="sticky-element"`.

Regel 3 stelt de afstand in vanaf de bovenkant van het venster waarop het element `sticky` wordt (de positie wordt vastgezet).