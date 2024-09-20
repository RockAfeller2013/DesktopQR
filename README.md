# Navigate to your project folder
cd /path/to/your/project

# Create a virtual environment using Python 3
python3 -m venv qr-env

# Activate the virtual environment
# On Windows
qr-env\Scripts\activate

# On macOS/Linux
source qr-env/bin/activate

# Install the dependencies from requirements.txt
pip install -r requirements.txt

# Install zbar library
# On macOS
brew install zbar

# On Ubuntu/Linux
sudo apt-get install libzbar0

# On Windows (you'll need to manually install zbar binaries)

# Run your Python script
python3 qr_code_reader.py

# Deactivate the virtual environment (optional)
deactivate
