In particle physics, accurate jet tagging plays a crucial role, enabling the identification of events originating
from different physical processes; a wide range of Deep Neural Network (DNN) approaches have been explored for this task. 
The current state of the art is represented by ParT, a transformer-based model. 

Recently, the **xLSTM architecture has been introduced**, a redesigned recurrent neural network that achieves performance comparable to, 
in some tasks even surpassing, transformer models in natural language modeling.
In this work **we present**, to the best of our knowledge, **the first application of xLSTM to jet tagging**, initially focusing on the
isolation of **top-quark events**. We build the architecture and evaluate its performance on established jet tagging benchmarks,
comparing it against simpler LSTM-based baselines. 

For the binary classification, the xLSTM JetTagger does not outperform standard LSTM architectures. However, **in the mutliclass classification** problem, the best **xLSTM model outperforms the LSTM in every major metric (AUC, partial AUC and TPR at low FPRs)**. Gains are modest but consistent, especially at stricter operating points (low FPR). Moreover, we find that a simple one M-block model with 5.4k params already obtains satisfactory results with 94.71% average AUC.   
