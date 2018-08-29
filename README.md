# extrem
18:23:25.732 T:140144638158592   DEBUG:     [PLUGIN] Vstream: could not load site: extreme-down error: timed out
18:23:25.732 T:140144638158592   ERROR: Traceback (most recent call last):
18:23:25.732 T:140144638158592   ERROR:   File "/home/venom/.kodi/addons/plugin.video.vstream/default.py", line 138, in parseUrl
18:23:25.733 T:140144638158592   ERROR:     function()
18:23:25.733 T:140144638158592   ERROR:   File "/home/venom/.kodi/addons/plugin.video.vstream/resources/sites/extreme-down.py", line 73, in showMovies
18:23:25.733 T:140144638158592   ERROR:     sHtmlContent = oRequestHandler.request()
18:23:25.733 T:140144638158592   ERROR:   File "/home/venom/.kodi/addons/plugin.video.vstream/resources/lib/handler/requestHandler.py", line 98, in request
18:23:25.733 T:140144638158592   ERROR:     return self.__callRequest()
18:23:25.733 T:140144638158592   ERROR:   File "/home/venom/.kodi/addons/plugin.video.vstream/resources/lib/handler/requestHandler.py", line 139, in __callRequest
18:23:25.733 T:140144638158592   ERROR:     oResponse = urllib2.urlopen(oRequest, timeout = self.__timeout)
18:23:25.733 T:140144638158592   ERROR:   File "/usr/lib/python2.7/urllib2.py", line 154, in urlopen
18:23:25.733 T:140144638158592   ERROR:     return opener.open(url, data, timeout)
18:23:25.733 T:140144638158592   ERROR:   File "/usr/lib/python2.7/urllib2.py", line 429, in open
18:23:25.734 T:140144638158592   ERROR:     response = self._open(req, data)
18:23:25.734 T:140144638158592   ERROR:   File "/usr/lib/python2.7/urllib2.py", line 447, in _open
18:23:25.734 T:140144638158592   ERROR:     '_open', req)
18:23:25.734 T:140144638158592   ERROR:   File "/usr/lib/python2.7/urllib2.py", line 407, in _call_chain
18:23:25.734 T:140144638158592   ERROR:     result = func(*args)
18:23:25.734 T:140144638158592   ERROR:   File "/usr/lib/python2.7/urllib2.py", line 1228, in http_open
18:23:25.734 T:140144638158592   ERROR:     return self.do_open(httplib.HTTPConnection, req)
18:23:25.734 T:140144638158592   ERROR:   File "/usr/lib/python2.7/urllib2.py", line 1201, in do_open
18:23:25.734 T:140144638158592   ERROR:     r = h.getresponse(buffering=True)
18:23:25.734 T:140144638158592   ERROR:   File "/usr/lib/python2.7/httplib.py", line 1121, in getresponse
18:23:25.734 T:140144638158592   ERROR:     response.begin()
18:23:25.734 T:140144638158592   ERROR:   File "/usr/lib/python2.7/httplib.py", line 438, in begin
18:23:25.734 T:140144638158592   ERROR:     version, status, reason = self._read_status()
18:23:25.734 T:140144638158592   ERROR:   File "/usr/lib/python2.7/httplib.py", line 394, in _read_status
18:23:25.734 T:140144638158592   ERROR:     line = self.fp.readline(_MAXLINE + 1)
18:23:25.734 T:140144638158592   ERROR:   File "/usr/lib/python2.7/socket.py", line 480, in readline
18:23:25.735 T:140144638158592   ERROR:     data = self._sock.recv(self._rbufsize)
18:23:25.735 T:140144638158592   ERROR: timeout: timed out
18:23:25.737 T:140144638158592   DEBUG:     [PLUGIN] Vstream: Table initialized
18:23:25.738 T:140144638158592    INFO: CPythonInvoker(21, /home/venom/.kodi/addons/plugin.video.vstream/default.py): script successfully run
18:23:25.752 T:140144638158592 WARNING: CPythonInvoker(21, /home/venom/.kodi/addons/plugin.video.vstream/default.py): the python script "/home/venom/.kodi/addons/plugin.video.vstream/default.py" has left several classes in memory that we couldn't clean up. The classes include: N9XBMCAddon9xbmcaddon5AddonE,N9XBMCAddon7xbmcgui6DialogE
18:23:25.752 T:140144638158592    INFO: Python script stopped
