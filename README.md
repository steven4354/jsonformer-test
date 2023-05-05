# jsonformer-test

testing out how good jsonformer actually is

results: 

using dolly with jsonformer is pretty expensive - $1k+ in hosting costs for a server with enough ram and sufficient spec'ed GPU

for testing, i used a 15GB (memory) a100 gpu on google colab for testing consumed about 14.7GB with the `-3b` parameter dolly model. use the `..._faster_inference` jupyter notebook to run jsonformer with gpu

using the `-12b` dolly parameter model crashed multiple times on colab even with a 15GB a100, probably need a GPU with more ram (which is expensive!!)

suggestions: 

retest this when jsonformer supports using chatgpt instead of hosting own model
