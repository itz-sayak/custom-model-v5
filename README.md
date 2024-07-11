# Custom model v5

## To get started

### 1. Requirements

Run `pip install -r requirements.txt` in terminal.

### 3. Train the model

Modify args in `train.py`. In custom-model-v5, some args are set as follows:

* `--weights`: `yolov5s.pt`
* `-cfg`: `models/our-model.yaml`
* `--hyp`: `data/hyps/hyp.scratch-high.yaml`

### 4. Evaluate the model

Modify args in `val.py`.

* `--weights`: the `best.pt` file in your result folder.
* `--task`: can be `val` or `test`.


