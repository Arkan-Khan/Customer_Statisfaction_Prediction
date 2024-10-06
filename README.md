# Project Setup Instructions

Follow the steps below to set up and run the project locally.

## Prerequisites

- Ensure you have [Python](https://www.python.org/downloads/) installed on your machine.
- Install [Git](https://git-scm.com/downloads) if you haven't already or download zip file.

## Steps to Set Up

1. **Clone the Repository**

   Open your terminal and run the following command to clone the repository:

   ```bash
   git clone https://github.com/Arkan-Khan/Customer_Statisfaction_Prediction.git

2. **Create a Virtual Environment**
   
    Navigate into the cloned repository directory:
    cd Customer_Statisfaction_Prediction
    Then, create a virtual environment:
    ```bash
    python -m venv venv
    ```
    Activate the Virtual Environment
    For Windows:
    ```bash
    venv\Scripts\activate
    ```
    For macOS/Linux:
    ```bash
    source venv/bin/activate
    ```

3. **Install Dependencies**
    Install the required packages by running:
    ```bash
    pip install -r requirements.txt
    ```

4. **Train the Model**
    After the dependencies are installed, train the model by executing:
    ```bash
    python train_model.py
    ```

5. **Run the Flask Application**
    Finally, run the Flask application with the following command:
    ```bash
    flask run
    ```

After running the command, you will see a link in the terminal. Open this link in your web browser to access the application.
