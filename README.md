# 🐨 Koala UI

#### Requires Python 2.7. (If you have macOS, maybe python is already instaled, if not install from link https://www.python.org/downloads/macos/)

## Configuration:
- Create a /Scripts folder in you project in Terminal<br>
> <code>mkdir Scripts</code><br>
> <code>cd Scripts</code><br>
- Inside /Scripts folder, download the GWB from apple git repo with command below.<br>
> <code>wget https://raw.githubusercontent.com/apple/swift/main/utils/gyb</code><br>
> <code>wget https://raw.githubusercontent.com/apple/swift/main/utils/gyb.py</code><br>
- Set write permission to files.<br>
> <code>chmod +x gyb</code><br>
> <code>chmod +x gyb.py</code>
- On your Build Phases click in the plus button
- Select New Run Script (you can rename to easy identify the script)
- Insert the Code below:
> <code>${PROJECT_DIR}/Scripts/generateTagFiles.sh</code>
- In your terminal, inside /Scripts folder execute the code:
- 


