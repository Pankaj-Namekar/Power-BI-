# SVG Visuals for Power BI

Custom SVG-based visuals used to extend Power BI beyond its native visual library, mainly for KPI cards and status indicators.

* SVG_Status Pill.pbix: a pill-shaped status indicator (e.g. On Track / At Risk / Behind) built with a dynamic SVG measure.
* SVG_Bar & Donut.pbix: custom bar and donut chart visuals rendered via SVG measures.

## How it works
These use Power BI's SVG-as-image-URL technique: a DAX measure returns a base64-encoded SVG string, which a card visual then renders as an image. This allows fully custom shapes, colors, and layouts that aren't available in Power BI's built-in visuals.

Open any file directly in Power BI Desktop to inspect the underlying DAX measures.
