# From Sand to Intelligence

Nine tables mapping the global AI economy, from physical production to industrial capabilities, trade, government policy and downstream effects.

**Editorial revision:** October 24, 2026. Nine tables, each with three columns, preserve the original 91 rows and reading order. Wording is shortened for blog embeds. [Research references](references.md) are kept outside the CSV files.

## Table index

| Table | Topic | Rows | What it explains |
| --- | --- | ---: | --- |
| [01](data/01_global_ai_industrial_pipeline.csv) | Global AI industrial pipeline | 11 | How materials, chips, infrastructure, models and applications connect. |
| [02](data/02_concentration_of_industrial_capabilities.csv) | Concentration of industrial capabilities | 11 | Geographic specializations and the dependencies behind them. |
| [03](data/03_critical_industrial_chokepoints.csv) | Critical industrial chokepoints | 10 | Why switching suppliers or technologies can be difficult. |
| [04](data/04_strategic_trade_routes_and_transport.csv) | Strategic trade routes and transport | 7 | Transport and energy corridors, disruption mechanisms and alternatives. |
| [05](data/05_government_controls_and_industrial_policy.csv) | Government controls and industrial policy | 11 | Jurisdictions, policy instruments and strategic effects. |
| [06](data/06_global_interdependencies.csv) | Global interdependencies | 10 | Inputs, outputs and potential disruption effects. |
| [07](data/07_economics_and_money_flows.csv) | Economics and money flows | 11 | Who pays, who receives spending, and where costs and financial risks arise. |
| [08](data/08_disruptions_and_downstream_effects.csv) | Disruptions and downstream effects | 10 | Plausible transmission mechanisms, responses and their limitations. |
| [09](data/09_competitors_and_structural_changes.csv) | Competitors and structural changes | 10 | Alternatives to existing concentrations and evidence needed to establish substitution. |

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

Files contain no spreadsheet formulas, title rows, merged cells or embedded images. Their numbered filenames preserve the intended reading order.

Abbreviations: EDA = electronic design automation; EUV = extreme ultraviolet; HBM = high-bandwidth memory; DRAM = dynamic random-access memory; GPU = graphics processing unit; CPU = central processing unit; API = application programming interface; IP = intellectual property; R&D = research and development; LNG = liquefied natural gas.

## Linking and publishing

After the files are pushed to GitHub, the raw URL pattern on the default branch is:

```text
https://raw.githubusercontent.com/snazrul1/blog_resources/main/articles/ai-supply-chain/data/<filename>.csv
```

Replace `<filename>.csv` with the complete numbered filename from the index. For a fixed snapshot, replace `main` with the desired commit SHA.

A raw URL supplies data to a renderer; it is not itself a formatted Medium table. This collection contains only CSV data and documentation, with no deployed renderer or publishing automation.

## Updating this collection

Keep filenames stable. Update facts, qualifications and source links together, record the new editorial revision date here, and preserve the distinction between observations and scenarios. Check that every file still parses as CSV and that each row has the same number of fields as its header.
