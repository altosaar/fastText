## Training

To train a model with a context based on sentences:
```
./sentence-context-example.sh
```

## Evaluation
An example evaluation file is in `./user_history.txt`.

To evaluate a trained model:
```
./fasttext rec_eval result/model.bin user_history.txt 20
```
