# CNN-for-classification-of-blood-cells

The code can be used in two ways:

<ol>
  <li> **Using the Trained Model for prediction on your dataset**</li>
  <p> The model was trained for predicting eight different type of blood cells and it can used for prediction as follows:</p>
    <ul>
      <li>Clone the repository and open the the file 'CNN_Prediction_Code.ipynb' in Jupyter Notebook</li>
      <li> Create a folder in the same directory and place all the images on which prediction need to be made. (a test folder is provided for reference)
</li>
      <li> In the .ipynb file, run the libraries block and function prediction block. Then call the function by passing the argument:
‘path’: path to your created folder. You will start seeing results for each file one by one.
</li>
      </ul>
  <p>It may be noted that the code expects the image to be in 'jpg' format and is of type 'unit8'. Furthermore, the code does not install any dependencies nor create any virtual environment as it was created on Google Colab.</p>  
  <p>You can find more detailed information in the "Detailed_Report.pdf".</p>
  <li> **Using the Model for your own dataset** </li>
  The code provides number of layers which allows the user to create different kind of models depending on their needs:
  <ul>
    <li>Dataset</li>
    <li>Convolutional Layer</li>
    <li>Activation Fucntions</li>
        <ul>
          <li>Hyperbolic Tangent Function</li>
          <li>ReLU</li> 
          <li>Leaky ReLU</li>
          <li>Softmax</li>
        </ul>
    <li>Pooling Layer</li>
    <li>Fully Connected Layer</li>
    <li>Cross Entropy Loss</li>
    <li>Evaluation Metrics</li>
          <ul>
            <li>Classification Accuary</li>
            <li>Confusion Matrix</li> 
          </ul>
    <li>Optimizers</li>
      <ul>
        <li>Gradient Descent</li>
        <li>Gradient Descent with Momentum</li> 
        <li>Nesterov Momentum</li>
        <li>AdaGrad</li>
        <li>RMSProp</li>
        <li>Adam</li>
      </ul>
    <li> Network</li>
    
  </ul>
  <p> You can find more details on how to work with these layers in "Training_on_different_dataset.pdf"</p>
  </ol>
    
