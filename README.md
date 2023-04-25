## wenet-model-parallel

Wenet is a very popular speech recognition toolkit, which itself supports traditional data parallel solutions.  However, the current recognition model is about to enter the era of large models (>=0.6B). There is no open source model parallelism and pipeline parallelism scheme in this field. This repo aims to explore such a scheme.
