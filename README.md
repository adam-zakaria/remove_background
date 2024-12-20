# Create venv
python3 -m venv myenv

# Activate venv
source venv/bin/activate

# Install requirements
pip install -r requirements.txt

# Run
This should work out of the box with the joe rogan test image
`python remove_background.py`

# Notes
We modified one line from the following:
https://huggingface.co/briaai/RMBG-2.0
