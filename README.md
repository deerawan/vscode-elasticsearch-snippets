# Elasticsearch Snippets for Visual Studio Code
Elasticsearch Snippets for Javascript and Typescript in Visual Studio Code. 

Support Elasticsearch 5.1

## Installation
Type `cmd-shift-p`/`ctrl-shift-p` to launch command palette and choose `Extensions: Install Extension`. Search for `Elasticsearch Snippets` and install.

## Usage
Type part of a snippet, press `enter` or `tab`

## Snippets

### Query
| Trigger | Description | Reference |
| ------- | ----------- | ---- |
| `es-term` | Query term  | [link](https://www.elastic.co/guide/en/elasticsearch/reference/5.1/query-dsl-term-query.html) |
| `es-terms` | Query terms  | [link](https://www.elastic.co/guide/en/elasticsearch/reference/5.1/query-dsl-terms-query.html) |
| `es-range` | Query range | [link](https://www.elastic.co/guide/en/elasticsearch/reference/5.1/query-dsl-range-query.html) |
| `es-exists` | Query exists | [link](https://www.elastic.co/guide/en/elasticsearch/reference/5.1/query-dsl-exists-query.html) |
| `es-prefix` | Query prefix | [link](https://www.elastic.co/guide/en/elasticsearch/reference/5.1/query-dsl-prefix-query.html) |
| `es-prefix-adv` | Query prefix + extra options | [link](https://www.elastic.co/guide/en/elasticsearch/reference/5.1/query-dsl-prefix-query.html) |
| `es-wildcard` | Query wildcard | [link](https://www.elastic.co/guide/en/elasticsearch/reference/5.1/query-dsl-wildcard-query.html) |
| `es-wildcard-adv` | Query wildcard + extra options | [link](https://www.elastic.co/guide/en/elasticsearch/reference/5.1/query-dsl-wildcard-query.html) |
| `es-regexp` | Query regexp | [link](https://www.elastic.co/guide/en/elasticsearch/reference/5.1/query-dsl-regexp-query.html) |
| `es-regexp-adv` | Query regexp + extra options | [link](https://www.elastic.co/guide/en/elasticsearch/reference/5.1/query-dsl-regexp-query.html) |
| `es-fuzzy` | Query fuzzy | [link](https://www.elastic.co/guide/en/elasticsearch/reference/5.1/query-dsl-fuzzy-query.html) |
| `es-fuzzy-adv` | Query fuzzy + extra options | [link](https://www.elastic.co/guide/en/elasticsearch/reference/5.1/query-dsl-fuzzy-query.html) |
| `es-type` | Query type | [link](https://www.elastic.co/guide/en/elasticsearch/reference/5.1/query-dsl-type-query.html) |
| `es-ids` | Query ids | [link](https://www.elastic.co/guide/en/elasticsearch/reference/5.1/query-dsl-ids-query.html) |

### Metric Aggregation
| Trigger | Description | Reference |
| ------- | ----------- | ---- |
| `es-agg-avg` | Agg avg  | [link](https://www.elastic.co/guide/en/elasticsearch/reference/5.1/search-aggregations-metrics-avg-aggregation.html) |
| `es-agg-cardinality` | Agg cardinality  | [link](https://www.elastic.co/guide/en/elasticsearch/reference/5.1/search-aggregations-metrics-cardinality-aggregation.html) |
| `es-agg-extstats` | Agg extended stats  | [link](https://www.elastic.co/guide/en/elasticsearch/reference/5.1/search-aggregations-metrics-extendedstats-aggregation.html) |
| `es-agg-geobounds` | Agg geo bounds  | [link](https://www.elastic.co/guide/en/elasticsearch/reference/5.1/search-aggregations-metrics-geobounds-aggregation.html) |
| `es-agg-geocentroid` | Agg geo centroid  | [link](https://www.elastic.co/guide/en/elasticsearch/reference/5.1/search-aggregations-metrics-geocentroid-aggregation.html) |
| `es-agg-max` | Agg max  | [link](https://www.elastic.co/guide/en/elasticsearch/reference/5.1/search-aggregations-metrics-max-aggregation.html) |
| `es-agg-min` | Agg min  | [link](https://www.elastic.co/guide/en/elasticsearch/reference/5.1/search-aggregations-metrics-min-aggregation.html) |
| `es-agg-percentiles` | Agg percentiles  | [link](https://www.elastic.co/guide/en/elasticsearch/reference/5.1/search-aggregations-metrics-percentile-aggregation.html) |
| `es-agg-percentiles-rank` | Agg percentiles rank  | [link](https://www.elastic.co/guide/en/elasticsearch/reference/5.1/search-aggregations-metrics-percentile-rank-aggregation.html) |
| `es-agg-scripted-metric` | Agg scripted metric  | [link](https://www.elastic.co/guide/en/elasticsearch/reference/5.1/search-aggregations-metrics-scripted-metric-aggregation.html) |
| `es-agg-stats` | Agg stats  | [link](https://www.elastic.co/guide/en/elasticsearch/reference/5.1/search-aggregations-metrics-stats-aggregation.html) |
| `es-agg-sum` | Agg sum  | [link](https://www.elastic.co/guide/en/elasticsearch/reference/5.1/search-aggregations-metrics-sum-aggregation.html) |
| `es-agg-top-hits` | Agg top hits  | [link](https://www.elastic.co/guide/en/elasticsearch/reference/5.1/search-aggregations-metrics-top-hits-aggregation.html) |
| `es-agg-value-count` | Agg value count  | [link](https://www.elastic.co/guide/en/elasticsearch/reference/5.1/search-aggregations-metrics-valuecount-aggregation.html) |

### Bucket Aggregation
| Trigger | Description | Reference |
| ------- | ----------- | ---- |
| `es-agg-children` | Agg children  | [link](https://www.elastic.co/guide/en/elasticsearch/reference/5.1/search-aggregations-bucket-children-aggregation.html) |
| `es-agg-date-histogram` | Agg date histogram  | [link](https://www.elastic.co/guide/en/elasticsearch/reference/5.1/search-aggregations-bucket-datehistogram-aggregation.html) |
| `es-agg-date-range` | Agg date range  | [link](https://www.elastic.co/guide/en/elasticsearch/reference/5.1/search-aggregations-bucket-daterange-aggregation.html) |
| `es-agg-div-sampler` | Agg diversified sampler  | [link](https://www.elastic.co/guide/en/elasticsearch/reference/5.1/search-aggregations-bucket-diversified-sampler-aggregation.html) |
| `es-agg-geo-distance` | Agg geo distance  | [link](https://www.elastic.co/guide/en/elasticsearch/reference/5.1/search-aggregations-bucket-geodistance-aggregation.html) |
| `es-agg-geohash-grid` | Agg geo hash grid  | [link](https://www.elastic.co/guide/en/elasticsearch/reference/5.1/search-aggregations-bucket-geohashgrid-aggregation.html) |
| `es-agg-global` | Agg geo global  | [link](https://www.elastic.co/guide/en/elasticsearch/reference/5.1/search-aggregations-bucket-global-aggregation.html) |
| `es-agg-histogram` | Agg histogram  | [link](https://www.elastic.co/guide/en/elasticsearch/reference/5.1/search-aggregations-bucket-histogram-aggregation.html) |
| `es-agg-iprange` | Agg IP range  | [link](https://www.elastic.co/guide/en/elasticsearch/reference/5.1/search-aggregations-bucket-iprange-aggregation.html) |
| `es-agg-missing` | Agg missing  | [link](https://www.elastic.co/guide/en/elasticsearch/reference/5.1/search-aggregations-bucket-missing-aggregation.html) |
| `es-agg-nested` | Agg nested  | [link](https://www.elastic.co/guide/en/elasticsearch/reference/5.1/search-aggregations-bucket-nested-aggregation.html) |
| `es-agg-range` | Agg range  | [link](https://www.elastic.co/guide/en/elasticsearch/reference/5.1/search-aggregations-bucket-range-aggregation.html) |
| `es-agg-reverse-nested` | Agg reverse nested  | [link](https://www.elastic.co/guide/en/elasticsearch/reference/5.1/search-aggregations-bucket-reverse-nested-aggregation.html) |
| `es-agg-sig-terms` | Agg significant terms  | [link](https://www.elastic.co/guide/en/elasticsearch/reference/5.1/search-aggregations-bucket-significantterms-aggregation.html) |
| `es-agg-terms` | Agg agg terms  | [link](https://www.elastic.co/guide/en/elasticsearch/reference/5.1/search-aggregations-bucket-terms-aggregation.html) |