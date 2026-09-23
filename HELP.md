# HazBIM Help and Quick Start

HazBIM is a productivity suite for Autodesk Revit. It adds a dedicated **HazBIM** ribbon tab. Hover over any HazBIM ribbon command and press **F1** to open the relevant section of this guide. You can also press **F1** while a HazBIM tool, result, sign-in, About, or update window is active.

## Getting started

1. Install the HazBIM package for your Revit version and restart Revit.
2. Open the **HazBIM** ribbon tab.
3. Select a tool. On first use, enter the HazBIM account credentials supplied by the developer.
4. To request a seven-day trial account or purchase a license, email [hazem.r.elhusieny@gmail.com](mailto:hazem.r.elhusieny@gmail.com).

HazBIM requires an internet connection for the initial sign-in and periodic license verification. After a successful online sign-in, eligible accounts can use the encrypted offline license cache for up to five days.

## About and support

Shows the installed HazBIM version, release information, developer contact details, the Privacy Policy, and this Help page.

## Updates

Checks the selected Stable or Beta channel for a compatible HazBIM release. An update check reads release information from the HazBIM Releases repository on GitHub. Installing an update requires closing Revit and AutoCAD.

## Magic Join

Joins architectural and structural elements using a configurable priority order. Review the selected categories and priority before applying changes to a production model.

## Split

Splits eligible multi-story structural columns and walls into level-by-level elements. Save or synchronize the model before running a large operation and review the result summary for elements that could not be split safely.

## Smart Dimensions

Creates dimensions and tags for supported structural columns and walls according to the selections and settings shown in the tool window.

## Renumber Piles

Renumbers piles using the selected direction, tolerance, digit count, and sequencing mode. Preview the ordering before applying it.

## Align Viewports

Aligns viewport positions across selected sheets by matching their scope boxes. Confirm that the source and destination views use the intended scope boxes before applying the alignment.

## SheetGen

Creates, duplicates, and renames floor-plan views from project levels. Review the naming rules and selected levels before creating views.

## ExportEX

Batch-exports selected sheets and printable views to supported formats such as PDF, DWG, DWF, IFC, NWC, DGN, and images. Available formats and settings depend on the installed Revit version and external print/export components. Review the export result window for skipped or failed items.

## Filter by Value

Creates and applies view filters from element parameter values. Confirm the selected categories, parameter, values, colors, and target view before creating filters.

## Reassign Level

Moves eligible level-dependent elements from one level to another while compensating offsets to preserve their physical 3D position. Review the result summary and unchanged element IDs after the operation.

## Switch Grids to 2D

Changes the visible grid extents in the active view to view-specific 2D extents.

## Switch Grids to 3D

Changes the visible grid extents in the active view to model-wide 3D extents.

## Export Schedule

Exports the active Revit schedule to an Excel workbook with element synchronization metadata. Keep the generated workbook structure intact if you plan to import changes.

## Import Schedule

Reads a compatible workbook created by **Export Schedule**, previews changes, and updates writable Revit parameters after confirmation. Work on a backup or synchronized model and review the preview before applying changes.

## Troubleshooting

- If sign-in fails, verify the username and password supplied by the developer and confirm that the computer can reach the licensing service.
- If offline access has expired, connect to the internet and sign in again to refresh it.
- If a tool is unavailable, open an appropriate Revit project/view and check the prerequisites in its window.
- For support, email [hazem.r.elhusieny@gmail.com](mailto:hazem.r.elhusieny@gmail.com) with the Revit version, HazBIM version, tool name, and a description of the issue.

See the [HazBIM Privacy Policy](PRIVACY.md) for information about licensing, updates, and stored data.
