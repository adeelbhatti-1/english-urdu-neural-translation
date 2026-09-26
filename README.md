# English Urdu Neural Translation

English-to-Urdu sequence-to-sequence translation experiments using recurrent neural networks.

## Contents

| File | Original filename |
|---|---|
| [notebooks/01_character_level_translation.ipynb](notebooks/01_character_level_translation.ipynb) | english-urdu-language-translation final submission.ipynb |
| [notebooks/02_alternative_translation_experiment.ipynb](notebooks/02_alternative_translation_experiment.ipynb) | ENGURDU2.ipynb |

## Run

For Python notebooks, install the inferred dependencies:

```bash
python -m pip install -r requirements.txt
python -m jupyterlab
```

Open a notebook and run cells from the beginning. Alternatively upload the notebook to Google Colab. Replace local or Google Drive paths with your own data locations before running. Notebooks are independent unless explicitly stated otherwise. For C++ files, compile and run each example separately with a compatible C++ compiler.

## Status and limitations

These are two separate experiments, not sequential stages of one pipeline. Supply the parallel corpus at the paths expected by each notebook. Document the corpus source and permitted use. Translation quality has not been independently evaluated; historical Keras APIs may need adaptation.

This collection was organised from existing files. Code-cell contents were preserved; saved outputs, execution counts, and transient notebook metadata were removed. The notebooks have not been executed as part of this preparation. Dependencies are inferred and unpinned, not a tested environment lockfile.

## Results

Run the examples to regenerate results. No accuracy, performance, or correctness claims are made here.

## Provenance

See [SOURCE_MAP.csv](SOURCE_MAP.csv) for the source archive and original filename. Preserve existing acknowledgements. No blanket open-source licence has been added because rights for adapted course material and datasets have not been established.
