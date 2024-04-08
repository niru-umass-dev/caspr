# caspr
CASPR: Automated Evaluation Metric for Measuring Contrast

JSON contains a List of Entity Pairs - Each Entity Pair has one Entry in the List
Only the modified summaries are present in the data file. Original reference summaries are to be found in the CoCoSUM dataset.
Data Format per JSON Entry:
{
  "entity_a": "Entity A's ID",
  "entity_b": "Entity B's ID",
  "syn_low_contrast": "Synthetic Low Contrast Summary",
  "syn_high_contrast": "Synthetic High Contrast Summary",
  "paraphrase_a": "Paraphrase of A's Reference Summary",
  "paraphrase_b": "Paraphrase of B's Reference Summary"
}
