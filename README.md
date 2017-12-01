# safetynets

Save assumptions and charecteristics of data into a `safety_net` object. Both the train set and new sets that will be scored by the model can be checked by the `safety_net`.

Package explicetely designed to complement `recipes` package by Max Kuhn. It will use the same logic by stepwise adding new threads (analogy to steps) to the net, than span (analogy to prep) the net and finally run datasets through it.
