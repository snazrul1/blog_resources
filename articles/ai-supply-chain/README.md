# From Sand to Intelligence

Nine tables mapping the global AI economy, from physical production to industrial capabilities, trade, government policy and downstream effects.

**Editorial revision:** October 24, 2026. Nine tables, each with three columns, preserve the original 91 rows and reading order. Wording is shortened for blog embeds. [Research references](references.md) are kept outside the CSV files.

## Table index

| Table | Topic | Rows | What it explains | Datawrapper |
| --- | --- | ---: | --- | --- |
| [01](data/01_global_ai_industrial_pipeline.csv) | Global AI industrial pipeline | 11 | How materials, chips, infrastructure, models and applications connect. | [Published table](https://datawrapper.dwcdn.net/yi9o5/2/) |
| [02](data/02_concentration_of_industrial_capabilities.csv) | Concentration of industrial capabilities | 11 | Geographic specializations and the dependencies behind them. | [Published table](https://datawrapper.dwcdn.net/xHoKx/1/) |
| [03](data/03_critical_industrial_chokepoints.csv) | Critical industrial chokepoints | 10 | Why switching suppliers or technologies can be difficult. | [Published table](https://datawrapper.dwcdn.net/TPeT6/1/) |
| [04](data/04_strategic_trade_routes_and_transport.csv) | Strategic trade routes and transport | 7 | Transport and energy corridors, disruption mechanisms and alternatives. | [Published table](https://datawrapper.dwcdn.net/gDyq8/1/) |
| [05](data/05_government_controls_and_industrial_policy.csv) | Government controls and industrial policy | 11 | Jurisdictions, policy instruments and strategic effects. | [Published table](https://datawrapper.dwcdn.net/lrnJU/1/) |
| [06](data/06_global_interdependencies.csv) | Global interdependencies | 10 | Inputs, outputs and potential disruption effects. | [Published table](https://datawrapper.dwcdn.net/Q3VrP/1/) |
| [07](data/07_economics_and_money_flows.csv) | Economics and money flows | 11 | Who pays, who receives spending, and where costs and financial risks arise. | [Published table](https://datawrapper.dwcdn.net/WiPQi/1/) |
| [08](data/08_disruptions_and_downstream_effects.csv) | Disruptions and downstream effects | 10 | Plausible transmission mechanisms, responses and their limitations. | [Published table](https://datawrapper.dwcdn.net/kiORv/1/) |
| [09](data/09_competitors_and_structural_changes.csv) | Competitors and structural changes | 10 | Alternatives to existing concentrations and evidence needed to establish substitution. | [Published table](https://datawrapper.dwcdn.net/JQnk6/1/) |

## Reading the tables

- Company examples are illustrative, not exhaustive rankings. Headquarters, ownership, manufacturing locations and legal jurisdiction are different concepts.
- Substitution ratings in Table 03 are qualitative editorial assessments, not measured industry-wide scores.
- Table 04 describes transport exposure, not current route availability or measured AI-specific cargo flows.
- Table 05 distinguishes licensing from bans, domestic legal authority from foreign controls, and announced programs from delivered capacity. Its references should be revisited before making claims about rules in force at a later publication date.
- Table 06 covers dependence on inputs and markets, alongside possible effects on the industry or its customers. Tables 06 and 08 present conditional analysis, not predictions or probability estimates.
- Spending and revenue across Table 07 overlap; adding the rows would double-count intermediate transactions. Financing and productivity benefits are not customer revenue.
- Table 09 distinguishes commercial alternatives, development efforts and evidence of meaningful substitution. Announced investments do not establish qualified operating capacity.

## File conventions

Each CSV has one header row and exactly three columns. Related fields from the original four-column tables are combined. There are no separate notes or source columns. Background sources are in [Research references](references.md); scenario analysis and qualitative judgments are editorial synthesis.

Cells use `<b>` for labels and `<br>` for line breaks in Datawrapper. Descriptions appear below labels, and Table 01 lists each country on a separate line with a bullet. Plain CSV viewers may display these tags literally.

Files contain no spreadsheet formulas, title rows, merged cells or embedded images. Their numbered filenames preserve the intended reading order.

Abbreviations: EDA = electronic design automation; EUV = extreme ultraviolet; HBM = high-bandwidth memory; DRAM = dynamic random-access memory; GPU = graphics processing unit; CPU = central processing unit; API = application programming interface; IP = intellectual property; R&D = research and development; LNG = liquefied natural gas.

## Linking and publishing

[Datawrapper mappings](datawrapper.json) connect each published table to its exact CSV path, live raw URL, editor and public embed URL. All nine tables are published in the accessible signed-in account; previous workspace IDs and URLs are retained in the mapping. The mapping records the CSV commit used at publication and preserves a commit-specific snapshot. The live source can change independently of that snapshot, including after publication.

Table 01 was recreated in the accessible account on October 24, 2026. Its original three columns remain visible on both desktop and mobile, with wrapping text, bold headers and alternating row shading. Mobile card fallback is disabled. Body and header text are approximately 13px so the columns fit a 350px embed. The source CSV is unchanged. The replacement is embedded in the unpublished Medium draft. The mapping retains the previous visualization ID.

For Medium, copy a published table URL from the index, paste it on a blank line and press Enter.

After the files are pushed to GitHub, the raw URL pattern on the default branch is:

```text
https://raw.githubusercontent.com/snazrul1/blog_resources/main/articles/ai-supply-chain/data/<filename>.csv
```

Replace `<filename>.csv` with the complete numbered filename from the index. For a fixed snapshot, replace `main` with the desired commit SHA.

A raw URL supplies data to a renderer; it is not itself a formatted Medium table. Datawrapper renders the tables from their linked CSVs. The repository contains data, references and publication mappings.

## Updating this collection

Keep filenames stable. Update facts, qualifications and source links together, record the new editorial revision date here, and preserve the distinction between observations and scenarios. Check that every file still parses as CSV and that each row has the same number of fields as its header.

Update `datawrapper.json` whenever a visualization is created, its source changes, or an approved publication is completed. Refresh the verified commit and snapshot URL after checking the draft against a new CSV revision.



All nine tables now retain a three-column grid on mobile. Tables 02–09 were recreated from their original live CSV sources on October 24, 2026, preserving titles, descriptions, notes and row order. Their new embeds are saved in the unpublished Medium draft. The saved embeds were checked through Medium’s embed renderer at 342px and 700px widths. The full-article preview intermittently leaves embeds blank, so final automatic heights inside that preview remain unverified.
