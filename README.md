# Submission files notes
* I have done everything in my report notebook file. So my model creation is at the start of that file and near the end of the file is my Introduction-Conclusion and then at the very end is my Advance Features.
* Image folder is used for my first advance feature. That resizes an image and runs its through the model.
* my_dir folder has files for my tuned model in it. This is used for my 2nd Advance feature which was apply hyperparameter tuning.






# Required Software:
* [Python 3.9+](https://www.python.org/downloads/)
* Text Editor for Python ([Visual Studio Code](https://code.visualstudio.com/) with [Python extension](https://marketplace.visualstudio.com/items?itemName=ms-python.python) installed is recommended)

Recommended:
* [Anaconda](https://www.anaconda.com/)
* [Virtualenv](https://virtualenv.pypa.io/en/latest/installation.html)

# Setting Up:
Install the libraries listed in the `requirements.txt` via the command:
```bash
pip install -r requirements.txt
```

Recommended to use a virtual environment either from either [virtualenv](https://docs.python.org/3/library/venv.html) or [anaconda](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html). This setup helps isolate project dependencies from user dependencies as to avoid version conflicts.

# Tensorboard:
Tensorboard is an added feature to the skeleton project. Run
```
tensorboard --logdir output/logs/
``` 
to run [tensorboard](https://github.com/tensorflow/tensorboard/blob/master/README.md). The main points of interests are accuracy and loss graphs. The tensorboard application can then be opened via the site `http://localhost:6006/`.
