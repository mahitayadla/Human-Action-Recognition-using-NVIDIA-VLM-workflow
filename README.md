**Action Detection in Videos using Gradio and NVIDIA API**

This project analyzes and compares action detection accuracy between two videos using a pre-trained model accessed via the NVIDIA VLM API. Below are the setup instructions, usage guide, and expected outputs.

**Setup**

**Prerequisites**

**Dependencies**: Install required Python packages: Gradio, etc

1\. **API Access**: Obtain an API key from the NVIDIA VLM API. Replace the API\_URL and

API\_KEY placeholders in the code with the appropriate values.

**Repository Files**

- code.ipynb: Full code

**Usage**

**Run the Application** Execute the script:

1. This launches a Gradio web interface locally
1. **Upload Videos**
- Upload two videos: one synthetic and one real.
- Specify the action (e.g., "running," "jumping") to analyze.
3. **Interact with the Interface**
- The app extracts frames, queries the API for action detection in each frame, and calculates detection accuracy.
- Outputs display the detection rates for both videos.

**Outputs to Expect**

- **UI Outputs**:
  - Detection accuracy for the specified action in both synthetic and real videos.
- **Logs**:
- Intermediate status updates, such as frame extraction and API responses.

**Example Results**

After processing, the app outputs:

Video 1 'running' Video 2 'running'

Detection Rate: 75.00% Detection Rate: 82.50%


