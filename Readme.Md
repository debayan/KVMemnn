# Pytorch: Key value memory networks for task oriented dialogue

The code here implements the one described in the paper Key-Value Retrieval Networks for Task-Oriented Dialogue <https://arxiv.org/pdf/1705.05414.pdf>


Dataset
Thanks to the authors for making the dataset public.
<https://nlp.stanford.edu/blog/a-new-multi-turn-multi-domain-task-oriented-dialogue-dataset/>

### Installation
Install the dependencies
```
numpy==1.14.5
pandas==0.23.3
pkg-resources==0.0.0
python-dateutil==2.7.3
pytz==2018.5
six==1.11.0
torch==0.4.0
```
To Run the training  use
```
python run.py
```

To run the examples once training is done

```
python examples.py
```

To run Bleu evaluation

```
cd utils/
python bleutest.py
```

We get Bleu score of 0.43 which is same as original Keras code accuracy at https://github.com/sunnysai12345/KVMemnn/blob/master/utils/Bleu.ipynb

License
----

MIT
