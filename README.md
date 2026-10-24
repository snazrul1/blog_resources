# Blog resources

Data and supporting material for articles on [Sadat Nazrul's Medium blog](https://medium.com/@sadatnazrul).

## Articles

| Collection | Resources | Description |
| --- | --- | --- |
| [From Sand to Intelligence](articles/ai-supply-chain/) | Nine CSV tables | The global AI supply chain, industrial capabilities, trade routes, policy, dependencies and economics. |

## Repository structure

```text
articles/
└── ai-supply-chain/
    ├── README.md
    └── data/
        ├── 01_global_ai_industrial_pipeline.csv
        ├── 02_concentration_of_industrial_capabilities.csv
        ├── 03_critical_industrial_chokepoints.csv
        ├── 04_strategic_trade_routes_and_transport.csv
        ├── 05_government_controls_and_industrial_policy.csv
        ├── 06_global_interdependencies.csv
        ├── 07_economics_and_money_flows.csv
        ├── 08_disruptions_and_downstream_effects.csv
        └── 09_competitors_and_structural_changes.csv
```

Each article collection has its own directory, a README explaining its resources, and a `data/` directory for reusable datasets. New collections should use descriptive, lowercase directory names separated by hyphens. Keep existing data paths stable so published links continue to work.

## Using the data

- Open a CSV on GitHub for a table preview, or use its **Raw** link in a compatible renderer.
- CSV files use UTF-8 encoding, a single header row and standard quoting for fields containing commas or quotation marks.
- Source URLs and qualifications travel with the data. Preserve relevant notes when displaying a table.
- A link to `main` follows later updates. Use a commit-specific link when an article needs a reproducible snapshot.

Medium does not natively turn a raw CSV URL into a formatted table. Rendering or embedding is a separate publishing step; a third-party embed must be supported by Medium. See [Medium's embed documentation](https://help.medium.com/hc/en-us/articles/214981378-Using-embeds).

Source material remains subject to its original terms. This repository does not assign a new license to third-party material.
