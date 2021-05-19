# rapspi_4_hunter

### prerequisite
#### camera
- sudo raspi-config
- interface
    - camera enable
- config (taking a sample photo)
```
raspistill -o image.jpg
```
#### picamera
```
pip install picamera
```
### usage
```
python camera.py
```
