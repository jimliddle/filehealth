# File Health
A html / javascript app that leverages the virus total api to scan files for viruses.

Initially a hash is sent to test whether the file has already been scanned to cut down on the upload.

The App uses CORS proxies which means the HTML file does not need to be served and can simply be double clicked and ran as a file.

History of files scanned is kept in the browser using indexeddb and can be cleared as required.

Two themes are provided, including one optimized for e-ink devices.
