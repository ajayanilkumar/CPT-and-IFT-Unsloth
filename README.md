# CPT-and-IFT-Unsloth

This repository conatins a notebook that uses unsloth for domain training of Llama 3.2 3B on a small Medical Dataset of 2 PDFs and an Instruction Dataset of 40 rows.

`PDFs` folder has 2 files from the NIH - *bipolardisorder.pdf* and *schizophrenia.pdf*

`datasets` folder has 3 files:
- `example1.md` has the contents of the Bipolar pdf.
- `example2.md` has the contents of the Schizophrenia pdf.
- `instruct_prompts.jsonl` has 40 synthetically generated prompt completions.

`Llam3_2_3B_NationalInstituteOfMentalHealth.ipynb` is the main notebook. Upload this on colab and upload the datasets folder into the contents.

