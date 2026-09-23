# Digital Treasury Pipeline — Revenue Monitoring Portal

This is a front-end-only government portal demonstration. It uses deterministic simulated data and makes no backend or network requests. A page refresh clears the in-memory department session and any pool connection key.

## Department access

Choose one of the five departments on the landing page to enter. Four departments have view-only access. Project Administrator can edit the financial assumptions, allocation settings, and in-memory branding or pool connection settings.

## Deterministic data

The records are generated once per page load from a fixed seed and reference date of 24 September 2026. The footer checksum identifies the generated net-revenue series so the figures can be compared between reloads.

## Branding

The provided Zimbabwe Coat of Arms is used in the portal header. An administrator may upload a PNG, JPG, or SVG emblem for the current browser tab only.
