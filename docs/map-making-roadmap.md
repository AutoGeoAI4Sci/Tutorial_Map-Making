# Map-Making Roadmap

This roadmap sketches how the repository can grow from shared recordings into a practical tutorial on drawing maps.

## 1. Map Purpose

- Define the question the map should answer.
- Identify the intended reader.
- Decide whether the map is exploratory, explanatory, or publication-facing.

## 2. Spatial Data Preparation

- Check geometry types, coordinate reference systems, and spatial extent.
- Clean missing values, duplicate geometries, and invalid geometries.
- Decide which attributes should drive visual encoding.

## 3. Projection and Scale

- Choose a projection that fits the region and map purpose.
- Match scale to the intended claim.
- Avoid visual distortion that changes the interpretation of distance, area, or direction.

## 4. Symbolization

- Pick colors, line weights, point symbols, and classification methods.
- Use color only when it carries meaning.
- Keep categories readable for color-blind readers when possible.

## 5. Labels, Legends, and Layout

- Place labels so they help the reader rather than crowd the map.
- Write legends that explain the visual encoding directly.
- Include a title, scale bar, north arrow, data source, and author credit when they are useful.

## 6. Publication-Quality Export

- Export at the correct size and resolution.
- Check text size after export.
- Save editable and archival versions when possible.

## 7. Reproducible Workflows

- Keep input data, scripts, and outputs organized.
- Record software versions and data sources.
- Use notebooks or scripts when a map needs to be regenerated.

## 8. AI-Assisted Map-Making

- Use AI tools to review visual hierarchy, write captions, generate checklists, or draft code.
- Verify all spatial operations and data interpretation manually.
- Treat AI suggestions as design review, not as a substitute for cartographic judgment.
