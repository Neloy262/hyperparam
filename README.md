You can find the custom dataset that we created on huggingface - https://huggingface.co/datasets/ysr/rust-sft-training

To use the model locally please follow the given steps
1. Install Ollama
2. Download our trained model from https://huggingface.co/ysr/hyperpara-1.3b-v1-gguf/tree/main
3. Clone this repository. You will see there is a file named Modelfile.txt.
4. Make sure the model(gguf file) and the Modelfile.txt are in the same directory.
5. If you are using windows open powershell. On linux you can use the terminal.
6. Run the command - ollama create hyperparam-rust -f path of Modelfile.txt
7. Open vscode and install the continue extension.
8. After installation switch to the continue tab.
9. On the bottom left corner you will see a list of models.
10. If step 6 ran without any problem you should see a model named hyperparam-rust.
