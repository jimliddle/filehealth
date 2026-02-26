# File Health
A html / javascript app that leverages the VirusTotal api to scan files for viruses. A VirusTotal API Key is required.

Although this can be downloaded, it is also hosted on Github Pages at: https://jimliddle.github.io/filehealth/ (all state resides in the client browser).

Initially a hash is sent to test whether the file has already been scanned to cut down on the upload.

The App uses CORS proxies which means the HTML file does not need to be served and can simply be double clicked and ran as a file.

History of files scanned is kept in the browser using indexeddb and can be cleared as required.

Two themes are provided, including one optimized for e-ink devices.

<img width="847" height="758" alt="screenshot" src="https://github.com/user-attachments/assets/c2f488b4-5521-43c3-bfc8-bb1e454f0c56" />

