# Fusion-Architecture-RNN-Models-with-Optimized-Cyclic-Learning-Rate-Scheduler

<p align="justify">
In the Fusion Architecture, we have utilized merged models like CNN+BiLSTM+CNN, BiLSTM+CNN+BiLSTM. The CNN layers in this hybrid model extract local features from the input data. The output of the CNN layers is then passed into the BiLSTM layers. The BiLSTM layers capture the sequential dependencies in the input data by processing it in both forward and backward directions. Finally, additional CNN layers are sometimes added after the BiLSTM layers to refine the extracted features further and capture higher-level representations. Thus Fusion models capture both local and contextual information from the input data. 

On the other hand, Instead of using a static or constant learning rate, we have utilized Cyclic Learning Rate(CLR). It cycles the learning rate between a fixed upper and lower bound. Further, we have optimized it by automatizing the global minima finder from the loss vs. learning rate curve.  
</p>

<p align="center">
  <img src="https://www.linkpicture.com/q/Screenshot-2023-07-03-205514.png" alt="Optimized CLR">
</p>



