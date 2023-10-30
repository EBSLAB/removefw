# TokenizeText find and remove phrase:

- Installed the following python module:
    ```
    >>> python3 -m venv venv
    >>> source venv/bin/activate
    >>> pip install polyglot-tokenizer==2.0.2
    ```

## Run the below command: to run script:
```
>>> python removefw.py --input in.txt --phrase_list swl_hin_uniq5325.txt --output output.txt --lang hi --split_sen True
```

## Program will generate Three Output:
- 1- singleLineOutput.txt: Contains the all sentences in single line after joining the lines.
- 2- Generate the sentence level output.
- 3- Final output: It will contain the output after removing the phrases.


