pimatic filebrowser plugin
===========================
A simpe web file browser for a local directory

Configuration:
--------------

    {
       "plugin": "filebrowser",
       "mappings": [
         {
           "path": "/files",
           "directory": "/media/usb1"
         }
       ]
     }

With this config you can browse your files in `/media/usb1` with `http://your-ip/files`.