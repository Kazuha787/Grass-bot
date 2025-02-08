
## Paste your proxies inside ```proxy_list.txt``` and the User ID inside ```id.txt```
# [GET PROXIES FROM HERE](https://app.proxies.fo/ref/617d744d-615f-1b41-bf9d-e4692763a7bd)
# .[JOIN MY TELEGRAM CHANNEL](https://t.me/Offical_Im_kazuha)
# How to Get GRASS User ID

1. Open your browser and login to the GRASS dashboard.
2. Press `F12` to open the **Inspect Elements** panel.
3. Go to the **Console** tab and paste the following code:

   ```javascript
   localStorage.getItem('userId')
   ```

4. You will receive your user ID, which looks like this: `"2oT4xCkPYSNyBp........"`
5. If you can't paste, type allow pasting and press Enter, then paste the line above.

## Recommended Python Version

It is recommended to use **Python 3.10**.  
[Download Python 3.10 here](https://www.python.org/downloads/release/python-3100/).

## Install Requirements

Run the following command to install the necessary packages:

```bash
pip install -r requirements.txt
```

## Running the Script

```bash
python run.py
```
## FOR ANDROID

# How to Get GRASS User ID Using Android Device

1. Download and install [Kiwi Browser](https://play.google.com/store/apps/details?id=com.kiwibrowser.browser&hl=en).
2. Login to the GRASS web and go to the dashboard.
3. Open the **Developer Tools** in the Kiwi browser.
4. Go to the **Console** tab and paste this code:

   ```javascript
   localStorage.getItem('userId')
   ```

5. If you can't paste, type `allow pasting` and press Enter, then paste the line above.

## Configure Termux

After installing Termux, ensure you have allowed storage permission for Termux (device app) settings.  
Alternatively, run this command in Termux:

```bash
termux-setup-storage
```

### Install Python 3.10

Run the following commands:

```bash
pkg update && upgrade
pkg install tur-repo
pkg install python-is-python3.10
pkg install -y rust binutils
CARGO_BUILD_TARGET="$(rustc -Vv | grep "host" | awk '{print $2}')" pip install maturin
```

## Clone This Script and change directory.
```
pkg install git
```
```
git clone https://github.com/Kazuha787/Grass-bot.git
```
```
cd Grass-bot
```
## Install Requirements
```bash
pip install -r requirements.txt
```
## Use nano to Paste your id inside ```id.txt``` and proxies inside ```proxy_list.txt```
```
pkg install nano
```
```
nano id.txt
```
```
nano proxy_list.txt
```
## Run the Script
```
python run.py
```
or
```
python3.10 run.py
```
