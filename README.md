# Install dependencies
pkg update && pkg upgrade -y
pkg install python python-pip -y
pip install requests beautifulsoup4

# Save the script as benzo-cracker.py
# Then run:
python benzo-cracker.py
