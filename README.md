### Run MLFLow

```mlflow ui
# open http://127.0.0.1:5000
```


### Predictions
ror: No such command 'print-input-schema'.
(venv) larawehbe@Laras-MacBook-Pro mlflow % curl -X POST http://127.0.0.1:5002/invocations \
  -H "Content-Type: application/json" \
  -d '{
    "dataframe_split": {
      "columns": ["sepal length","sepal width","petal length","petal width"],
      "data": [[5.1, 3.5, 1.4, 0.2]]
    }
  }'

{"predictions": [0]}%                                                      
| just make sure you export MLFLOW URI in the cmd