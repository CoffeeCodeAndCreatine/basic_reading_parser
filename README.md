# John's Basic Reading Parser
Needed a way to parse the text out of the John's Basic Reading Inventory. Ended up running a bit of OCR on the pdf, dumped that text into a json file, then wrote a python script to convert it to word documents.

## Requirements
1. python3
2. pip3  

## How to Build 
```bash
pip3 install -r requirements.txt
```
## How to Run
```bash
python3 json_reader.py

```

## Sample Output
```bash
output
├── form_a
│   ├── reading_charts
│   │   ├── grade_1
│   │   │   └── grade_1_size12.docx
│   │   ├── grade_2
│   │   │   └── grade_2_size12.docx
│   │   ├── grade_3
│   │   │   └── grade_3_size12.docx
│   │   ├── grade_4
│   │   │   └── grade_4_size12.docx
│   │   ├── grade_5
│   │   │   └── grade_5_size12.docx
│   │   ├── grade_6
│   │   │   └── grade_6_size12.docx
│   │   ├── grade_7
│   │   │   └── grade_7_size12.docx
│   │   ├── grade_8
│   │   │   └── grade_8_size12.docx
│   │   ├── pre_primer_1
│   │   │   └── pre_primer_1_size12.docx
│   │   ├── pre_primer_2
│   │   │   └── pre_primer_2_size12.docx
│   │   └── primer
│   │       └── primer_size12.docx
│   └── sight_words
│       ├── grade_1
│       │   └── grade_1_size12.docx
│       ├── grade_10
│       │   └── grade_10_size12.docx
│       ├── grade_11
│       │   └── grade_11_size12.docx
│       ├── grade_12
│       │   └── grade_12_size12.docx
│       ├── grade_2
│       │   └── grade_2_size12.docx
│       ├── grade_3
│       │   └── grade_3_size12.docx
│       ├── grade_4
│       │   └── grade_4_size12.docx
│       ├── grade_5
│       │   └── grade_5_size12.docx
│       ├── grade_6
│       │   └── grade_6_size12.docx
│       ├── grade_7
│       │   └── grade_7_size12.docx
│       ├── grade_8
│       │   └── grade_8_size12.docx
│       ├── grade_9
│       │   └── grade_9_size12.docx
│       ├── pre_primer
│       │   └── pre_primer_size12.docx
│       └── primer
│           └── primer_size12.docx
├── form_b
│   ├── reading_charts
│   │   ├── grade_1
│   │   │   └── grade_1_size12.docx
│   │   ├── grade_2
│   │   │   └── grade_2_size12.docx
│   │   ├── grade_3
│   │   │   └── grade_3_size12.docx
│   │   ├── grade_4
│   │   │   └── grade_4_size12.docx
│   │   ├── grade_5
│   │   │   └── grade_5_size12.docx
│   │   ├── grade_6
│   │   │   └── grade_6_size12.docx
│   │   ├── grade_7
│   │   │   └── grade_7_size12.docx
│   │   ├── grade_8
│   │   │   └── grade_8_size12.docx
│   │   ├── pre_primer_1
│   │   │   └── pre_primer_1_size12.docx
│   │   ├── pre_primer_2
│   │   │   └── pre_primer_2_size12.docx
│   │   └── primer
│   │       └── primer_size12.docx
│   └── sight_words
│       ├── grade_1
│       │   └── grade_1_size12.docx
│       ├── grade_10
│       │   └── grade_10_size12.docx
│       ├── grade_11
│       │   └── grade_11_size12.docx
│       ├── grade_12
│       │   └── grade_12_size12.docx
│       ├── grade_2
│       │   └── grade_2_size12.docx
│       ├── grade_3
│       │   └── grade_3_size12.docx
│       ├── grade_4
│       │   └── grade_4_size12.docx
│       ├── grade_5
│       │   └── grade_5_size12.docx
│       ├── grade_6
│       │   └── grade_6_size12.docx
│       ├── grade_7
│       │   └── grade_7_size12.docx
│       ├── grade_8
│       │   └── grade_8_size12.docx
│       ├── grade_9
│       │   └── grade_9_size12.docx
│       ├── pre_primer
│       │   └── pre_primer_size12.docx
│       └── primer
│           └── primer_size12.docx
├── form_c
│   ├── reading_charts
│   │   ├── grade_1
│   │   │   └── grade_1_size12.docx
│   │   ├── grade_2
│   │   │   └── grade_2_size12.docx
│   │   ├── grade_3
│   │   │   └── grade_3_size12.docx
│   │   ├── grade_4
│   │   │   └── grade_4_size12.docx
│   │   ├── grade_5
│   │   │   └── grade_5_size12.docx
│   │   ├── grade_6
│   │   │   └── grade_6_size12.docx
│   │   ├── grade_7
│   │   │   └── grade_7_size12.docx
│   │   ├── grade_8
│   │   │   └── grade_8_size12.docx
│   │   ├── pre_primer_1
│   │   │   └── pre_primer_1_size12.docx
│   │   ├── pre_primer_2
│   │   │   └── pre_primer_2_size12.docx
│   │   └── primer
│   │       └── primer_size12.docx
│   └── sight_words
│       ├── grade_1
│       │   └── grade_1_size12.docx
│       ├── grade_10
│       │   └── grade_10_size12.docx
│       ├── grade_11
│       │   └── grade_11_size12.docx
│       ├── grade_12
│       │   └── grade_12_size12.docx
│       ├── grade_2
│       │   └── grade_2_size12.docx
│       ├── grade_3
│       │   └── grade_3_size12.docx
│       ├── grade_4
│       │   └── grade_4_size12.docx
│       ├── grade_5
│       │   └── grade_5_size12.docx
│       ├── grade_6
│       │   └── grade_6_size12.docx
│       ├── grade_7
│       │   └── grade_7_size12.docx
│       ├── grade_8
│       │   └── grade_8_size12.docx
│       ├── grade_9
│       │   └── grade_9_size12.docx
│       ├── pre_primer
│       │   └── pre_primer_size12.docx
│       └── primer
│           └── primer_size12.docx
├── form_d
│   └── reading_charts
│       ├── grade_1
│       │   └── grade_1_size12.docx
│       ├── grade_2
│       │   └── grade_2_size12.docx
│       ├── grade_3
│       │   └── grade_3_size12.docx
│       ├── grade_4
│       │   └── grade_4_size12.docx
│       ├── grade_5
│       │   └── grade_5_size12.docx
│       ├── grade_6
│       │   └── grade_6_size12.docx
│       ├── grade_7
│       │   └── grade_7_size12.docx
│       ├── grade_8
│       │   └── grade_8_size12.docx
│       ├── pre_primer_1
│       │   └── pre_primer_1_size12.docx
│       ├── pre_primer_2
│       │   └── pre_primer_2_size12.docx
│       └── primer
│           └── primer_size12.docx
├── form_e
│   └── reading_charts
│       ├── grade_1
│       │   └── grade_1_size12.docx
│       ├── grade_2
│       │   └── grade_2_size12.docx
│       ├── grade_3
│       │   └── grade_3_size12.docx
│       ├── grade_4
│       │   └── grade_4_size12.docx
│       ├── grade_5
│       │   └── grade_5_size12.docx
│       ├── grade_6
│       │   └── grade_6_size12.docx
│       ├── grade_7
│       │   └── grade_7_size12.docx
│       ├── grade_8
│       │   └── grade_8_size12.docx
│       ├── pre_primer_1
│       │   └── pre_primer_1_size12.docx
│       ├── pre_primer_2
│       │   └── pre_primer_2_size12.docx
│       └── primer
│           └── primer_size12.docx
├── le_passages
│   ├── 10
│   │   └── 10_size12.docx
│   ├── 11
│   │   └── 11_size12.docx
│   ├── 12
│   │   └── 12_size12.docx
│   ├── 3
│   │   └── 3_size12.docx
│   ├── 4
│   │   └── 4_size12.docx
│   ├── 5
│   │   └── 5_size12.docx
│   ├── 6
│   │   └── 6_size12.docx
│   ├── 7
│   │   └── 7_size12.docx
│   ├── 8
│   │   └── 8_size12.docx
│   └── 9
│       └── 9_size12.docx
└── ln_passages
    ├── 10
    │   └── 10_size12.docx
    ├── 11
    │   └── 11_size12.docx
    ├── 12
    │   └── 12_size12.docx
    ├── 3
    │   └── 3_size12.docx
    ├── 4
    │   └── 4_size12.docx
    ├── 5
    │   └── 5_size12.docx
    ├── 6
    │   └── 6_size12.docx
    ├── 7
    │   └── 7_size12.docx
    ├── 8
    │   └── 8_size12.docx
    └── 9
        └── 9_size12.docx
```