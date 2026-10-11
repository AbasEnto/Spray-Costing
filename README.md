# Apple Orchard Pesticide Spray Cost Calculator | ICAR-CITH

**[Open the Online Apple Orchard Spray Cost Calculator](https://abasento.github.io/Spray-Costing/)**

A browser-based cost-estimation tool developed at the **ICAR-Central Institute of Temperate Horticulture (ICAR-CITH), Srinagar, Jammu & Kashmir, India**. It estimates the **insecticide material cost, spray application cost and combined cost** for a user-specified area of an apple orchard.

The model differentiates among **traditional, medium-density and high-density orchards** and their tree-age groups. It accounts for differences in spray-solution volume and estimates machinery ownership and operating costs using the assumptions documented in the underlying technical bulletin.

## How to use the calculator

1. Select the orchard system and corresponding tree-age group.
2. Select the insecticide formulation.
3. Enter the orchard area in kanal.
4. Choose the **ASA&BE** or **Straight-Line** machinery fixed-cost method.
5. Select **Calculate** to see material, application and total estimated costs for the entered area. Select **See Detailed Breakdown** for per-kanal and hourly components.

The model uses **historical Srinagar input prices as of 1 June 2024** and illustrative operating assumptions. Results are indicative cost estimates, not current quotations or pesticide-use recommendations. Mentioning a formulation does not constitute endorsement or authorization for a particular crop or location. Users should consult current applicable regulations, product labels and official advisories.

## Technical bulletin

**Shah, M. A., Tramboo, H. A., Rehman, S. A., Parvez, B., Nabi, S. U., Raja, W. H., Malik, G., Jaiswal, R., Mir, J. I., Sharma, O. C., & Verma, M. K. (2025).** *Estimation of the cost of insecticide application in apple orchards* (Technical Bulletin, Reference No. CITH/PME/2025/02, Edition 01). ICAR-Central Institute of Temperate Horticulture, Srinagar, J&K, India.

[Read the detailed Technical Bulletin (PDF)](https://abasento.github.io/Spray-Costing/technical-bulletin.pdf)

## Repository files

- `index.html` — web interface, site styling, search metadata and explanatory sections.
- `app.js` — calculator functions and interface behavior.
- `data.json` — orchard spray volumes, formulation-cost values and machinery assumptions.
- `technical-bulletin.pdf` — supporting methods and published reference tables.
- `sitemap.xml` — sitemap for search engines.
- `LICENSE.txt` — repository licensing terms.

## Copyright and license

© 2025 ICAR–Central Institute of Temperate Horticulture, Srinagar, J&K, India. All rights reserved, subject to the permissions expressly specified in the [repository's LICENSE.txt](LICENSE.txt).

For rights and permissions questions, consult the Institute and the repository's license terms.
