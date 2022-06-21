# SingleNeuron
SingleNeuron | perceptron

### commands

## Add URL -
[Git handbook](https://guides.github.com/introduction/git-handbook/)

<a href="https://www.w3schools.com">Visit W3Schools.com!</a>

## Add image -
![sample image](plots/or.png)

## Python code
```python
def main(data, modelName, plotName, eta, epochs):
    df = pd.DataFrame(data)
    print(df)
    X, y = prepare_data(df)
    model = Perceptron(eta=eta, epochs=epochs)
    model.fit(X, y)
    _ = model.total_loss()
    save_model(model, filename=modelName)
    save_plot(df, plotName, model)
```

## dataset

x1 | x2 | y
-|-|-
0|0|0
0|1|0
1|0|0
1|1|1

### 
* point 1
* point 2

1. point
