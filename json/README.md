Parse big json file
-------------------

To generate json file: `ruby generate_json.rb`

To compile all: `sh build.sh`

To run all: `sh run.sh`

# Benchmark

| Language        | Time,s  | Memory, Mb |
| --------------- | ------- | ---------- |
| Crystal Schema  | 1.18    | 256.1      |
| Crystal Pull    | 1.48    | 1.2        |
| Crystal         | 1.96    | 814.3      |
| Javascript Node | 5.24    | 624.2      |
| Ruby            | 8.19    | 1644.3     |
