# Strategy Comparison Report

- Queries: `10000`
- `k_eval`: `100`

- Comparison plot: `strategy_comparison_q10000_topk100.png`
- Planner routing plot: `planner_routing_q10000_topk100.png`

## Strategy Metrics

| Strategy | Total Time (s) | QPS | Recall@k | Routing Time (s) | Execution Time (s) |
| --- | --- | --- | --- | --- | --- |
| PRE | 33.759900 | 296.21 | 0.9999 |  |  |
| POST | 13.363100 | 748.33 | 0.6496 |  |  |
| ACORN | 16.367598 | 610.96 | 0.9075 |  |  |
| PLANNER | 11.384872 | 878.36 | 0.9070 | 1.052158 | 10.332714 |

## Planner Routing

| Route | Queries |
| --- | --- |
| PRE | 1217 |
| POST | 3827 |
| ACORN | 4956 |

## Planner Correlation Types

| Correlation | Queries |
| --- | --- |
| positive | 3958 |
| random | 252 |
| negative | 5790 |
