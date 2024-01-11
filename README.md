## Important Acknowledgment

Please note that the content presented here is not the original creation of the author, Zeily Garcia. This material is a reproduced version of an exercise sourced from [py-pkgs.org](https://py-pkgs.org/03-how-to-package-a-python). It is used solely for educational purposes as part of an assignment in a Data Science Master's program. 

## [Read The Docs Link](https://practice-pycounts-zeily-second.readthedocs.io/en/latest/example.html)

# pycounts

calculates counts of unique words it a text file

## Installation

```bash
$ pip install pycounts
```

## Usage

`pycounts` can be used to count words in a text file and plot results
as follows:

```python
from pycounts.pycounts import count_words
from pycounts.plotting import plot_words
import matplotlib.pyplot as plt

file_path = "test.txt"  # path to your file
counts = count_words(file_path)
fig = plot_words(counts, n=10)
plt.show()
```

## Contributing

Interested in contributing? Check out the contributing guidelines. Please note that this project is released with a Code of Conduct. By contributing to this project, you agree to abide by its terms.

## License

`pycounts` package, recreated by Zeily Garcia, is a replicate work based on the original package by Tomas Beuzen, available at [TomasBeuzen/pycounts on GitHub](https://github.com/TomasBeuzen/pycounts). Like the original package, it is licensed under the terms
of the MIT license.

## Credits

`pycounts` was created with [`cookiecutter`](https://cookiecutter.readthedocs.io/en/latest/) and the `py-pkgs-cookiecutter` [template](https://github.com/py-pkgs/py-pkgs-cookiecutter).
