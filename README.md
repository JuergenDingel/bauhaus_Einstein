# Solving Einstein's Puzzle with Bauhaus

## Summary

Go to, e.g., https://web.stanford.edu/~laurik/fsmbook/examples/Einstein%27sPuzzle.html for a description of Einstein's puzzle.
We use the Python library Bauhaus (https://bauhaus.readthedocs.io) to encode and solve it. The main purpose is to provide another example of the use of Bauhaus. As a project in CISC 204 it would probably be too simple (we'll use the CISC 204 project template nonetheless). Note that none of the expected documents are provided. 


## To run things

### Building
```docker build -t cisc204 .```

### Running
```docker run -it -v $(pwd):/PROJECT cisc204```


## Structure
### General or provided
* `documents`: Contains folders for both of your draft and final submissions. README.md files are included in both.
* `test.py`: Run this file to confirm that your submission has everything required. This essentially just means it will check for the right files and sufficient theory size.

### Custom code
* `run.py`: Contains code to build the encoding, solve it, and output the result.

