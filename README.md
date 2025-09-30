In particle physics, accurate jet tagging plays a crucial role, enabling the identification of events originating
from different physical processes; a wide range of Deep Neural Network (DNN) approaches have been explored for this task. 
The current state of the art is represented by ParT, a transformer-based model. 

Recently, the **xLSTM architecture has been introduced**, a redesigned recurrent neural network that achieves performance comparable to, 
in some tasks even surpassing, transformer models in natural language modeling.
In this work **we present**, to the best of our knowledge, **the first application of xLSTM to jet tagging**, focusing on the
isolation of **top-quark events**. We describe the architecture and evaluate its performance on established jet tagging benchmarks,
comparing it against simpler LSTM-based baselines. 
For this binary classification, the xLSTM JetTagger does not outperform
standard LSTM architectures. Further work is needed to assess
whether the architecture’s potential can be fully exploited on
the more complex problem of multi-class jet tagging, which is
of particular interest for low-level trigger systems.
