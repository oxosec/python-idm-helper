# python-idm-helper
Use IDM Api in python.

# EXAMPLE USAGE
```python

url = 'http://www.internetdownloadmanager.com/idman401.exe'
outputFolderPath = os.getcwd()
outputFileName = 'idman.exe'
customUserAgent = None
flag = 3 #see above the flag information
IDMHelper(url, outputFolderPath, outputFileName, flag, userAgent=customUserAgent).sendToIDM()

```
API REFERENCE: http://www.internetdownloadmanager.com/support/idm_api.html

Ps. I just made this idm helper for my python tools. Because my download speed is so slow when using built in downloader or aria2c. 
Hope this will be helpful to you also :)
