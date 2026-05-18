# Reference Benchmark Manifest

This folder contains the public benchmark infographics used by `pipeline-infographic-builder`.

The benchmark set is intentionally image-only. It does not include private reference documents, Excel workbooks, client data, tender data, or course source materials.

## Benchmark Files

| File | Workflow | Status | SHA256 |
|---|---|---|---|
| `01-monthly-report-agent.png` | Monthly Report Agent | User-provided gold-standard benchmark image | `6653EA32D39F6DA1E696B5E7E1F84A49442842A6347EB4FBC95867AC294ABE5C` |
| `02-rfi-agent.png` | RFI Agent | Generated after layout visibility QA passed: no clipping, no overflow, no tiny text | `4C320931C743A8A5DEA4989142C46661D02E67287D71F4B9615D4996C1E14032` |
| `03-method-statement-agent.png` | Method Statement Agent | Generated after layout visibility QA passed: no clipping, no overflow, no tiny text | `5C2637ABF8C875A296DBB1E5D5FDEAC95B64ED6985C47825EA158DAAD8B7A48C` |
| `04-tendering-agent.png` | Tendering Agent | Generated after layout visibility QA passed: no clipping, no overflow, no tiny text | `2B6712BDF1BE67FE87128F85ACAC5D7C79F5B62D2F2572BAB3F20EAF290A6B03` |

## QA Standard

For generated benchmarks, the layout visibility QA checked:

- Text clipping
- Container overflow
- Hidden text
- Tiny text
- Required structure: timeline, 8 workflow stages, ownership matrix, outputs, GO / CONTROL / STOP gates, business value, governance banner

The expected standard is:

```text
Status: PASS
clipping: None
overflow: None
tinyText: None
```
