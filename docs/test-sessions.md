### collection of test sessions, to verify the consistency of the "results"
The WebSocket ctor errors are our results.
These summaries/snippets were generated, filtered from the google-chrome console output with:
```bash
grep 'WebSocket connection' tmp.out \
	| sort \
	| sed -e "s/^.*'wss\:\/\///g" \
	> test-session-02.out
```
##### test-session-00
```
193-119-48-13.static.tpgi.com.au/' failed: WebSocket opening handshake timed out
193-119-48-13.static.tpgi.com.au:1111/' failed: Error in connection establishment: net::ERR_CONNECTION_TIMED_OUT
193-119-48-13.static.tpgi.com.au:42000/' failed: Error in connection establishment: net::ERR_CONNECTION_TIMED_OUT
193-119-48-13.static.tpgi.com.au:444/' failed: Error in connection establishment: net::ERR_CONNECTION_TIMED_OUT
193-119-48-13.static.tpgi.com.au:80/' failed: Error in connection establishment: net::ERR_CONNECTION_RESET
193-119-48-13.static.tpgi.com.au:81/' failed: Error in connection establishment: net::ERR_CONNECTION_TIMED_OUT
bitbucket.com/' failed: Error during WebSocket handshake: Unexpected response code: 301
bitbucket.com:55555/' failed: WebSocket opening handshake timed out
bitbucket.com:80/' failed: Error in connection establishment: net::ERR_SSL_PROTOCOL_ERROR
github.com/' failed: Error during WebSocket handshake: Unexpected response code: 200
github.com:55555/' failed: Error in connection establishment: net::ERR_CONNECTION_TIMED_OUT
github.com:80/' failed: Error in connection establishment: net::ERR_SSL_PROTOCOL_ERROR
mbohun.github.io/' failed: Error during WebSocket handshake: Unexpected response code: 200
mbohun.github.io:42424/' failed: WebSocket opening handshake timed out
mbohun.github.io:80/' failed: WebSocket opening handshake timed out
```
##### test-session-01
```
193-119-48-13.static.tpgi.com.au/' failed: WebSocket opening handshake timed out
193-119-48-13.static.tpgi.com.au:1111/' failed: Error in connection establishment: net::ERR_CONNECTION_TIMED_OUT
193-119-48-13.static.tpgi.com.au:42000/' failed: Error in connection establishment: net::ERR_CONNECTION_TIMED_OUT
193-119-48-13.static.tpgi.com.au:444/' failed: Error in connection establishment: net::ERR_CONNECTION_TIMED_OUT
193-119-48-13.static.tpgi.com.au:80/' failed: WebSocket opening handshake timed out
193-119-48-13.static.tpgi.com.au:81/' failed: Error in connection establishment: net::ERR_CONNECTION_TIMED_OUT
bitbucket.com/' failed: Error during WebSocket handshake: Unexpected response code: 301
bitbucket.com:55555/' failed: WebSocket opening handshake timed out
bitbucket.com:80/' failed: Error in connection establishment: net::ERR_SSL_PROTOCOL_ERROR
github.com/' failed: Error during WebSocket handshake: Unexpected response code: 200
github.com:55555/' failed: Error in connection establishment: net::ERR_CONNECTION_TIMED_OUT
github.com:80/' failed: Error in connection establishment: net::ERR_SSL_PROTOCOL_ERROR
mbohun.github.io/' failed: Error during WebSocket handshake: Unexpected response code: 200
mbohun.github.io:42424/' failed: WebSocket opening handshake timed out
mbohun.github.io:80/' failed: WebSocket opening handshake timed out
```
##### test-session-02
```
193-119-48-13.static.tpgi.com.au/' failed: WebSocket opening handshake timed out
193-119-48-13.static.tpgi.com.au:1111/' failed: Error in connection establishment: net::ERR_CONNECTION_TIMED_OUT
193-119-48-13.static.tpgi.com.au:42000/' failed: Error in connection establishment: net::ERR_CONNECTION_TIMED_OUT
193-119-48-13.static.tpgi.com.au:444/' failed: Error in connection establishment: net::ERR_CONNECTION_TIMED_OUT
193-119-48-13.static.tpgi.com.au:80/' failed: WebSocket opening handshake timed out
193-119-48-13.static.tpgi.com.au:81/' failed: Error in connection establishment: net::ERR_CONNECTION_TIMED_OUT
bitbucket.com/' failed: Error during WebSocket handshake: Unexpected response code: 301
bitbucket.com:55555/' failed: WebSocket opening handshake timed out
bitbucket.com:80/' failed: Error in connection establishment: net::ERR_SSL_PROTOCOL_ERROR
github.com/' failed: Error during WebSocket handshake: Unexpected response code: 200
github.com:55555/' failed: Error in connection establishment: net::ERR_CONNECTION_TIMED_OUT
github.com:80/' failed: Error in connection establishment: net::ERR_SSL_PROTOCOL_ERROR
mbohun.github.io/' failed: Error during WebSocket handshake: Unexpected response code: 200
mbohun.github.io:42424/' failed: WebSocket opening handshake timed out
mbohun.github.io:80/' failed: WebSocket opening handshake timed out
```
##### test-session-03
```
193-119-48-13.static.tpgi.com.au/' failed: Error in connection establishment: net::ERR_CERT_AUTHORITY_INVALID
193-119-48-13.static.tpgi.com.au:1111/' failed: Error in connection establishment: net::ERR_CONNECTION_REFUSED
193-119-48-13.static.tpgi.com.au:42000/' failed: Error in connection establishment: net::ERR_CONNECTION_REFUSED
193-119-48-13.static.tpgi.com.au:444/' failed: Error in connection establishment: net::ERR_CONNECTION_REFUSED
193-119-48-13.static.tpgi.com.au:80/' failed: Error in connection establishment: net::ERR_SSL_PROTOCOL_ERROR
193-119-48-13.static.tpgi.com.au:81/' failed: Error in connection establishment: net::ERR_CONNECTION_REFUSED
bitbucket.com/' failed: Error during WebSocket handshake: Unexpected response code: 301
bitbucket.com:55555/' failed: WebSocket opening handshake timed out
bitbucket.com:80/' failed: Error in connection establishment: net::ERR_SSL_PROTOCOL_ERROR
github.com/' failed: Error during WebSocket handshake: Unexpected response code: 200
github.com:55555/' failed: Error in connection establishment: net::ERR_CONNECTION_TIMED_OUT
github.com:80/' failed: Error in connection establishment: net::ERR_SSL_PROTOCOL_ERROR
mbohun.github.io/' failed: Error during WebSocket handshake: Unexpected response code: 200
mbohun.github.io:42424/' failed: WebSocket opening handshake timed out
mbohun.github.io:80/' failed: WebSocket opening handshake timed out
```
##### test-session-04
```
193-119-48-13.static.tpgi.com.au/' failed: Error in connection establishment: net::ERR_CERT_AUTHORITY_INVALID
193-119-48-13.static.tpgi.com.au:1111/' failed: Error in connection establishment: net::ERR_CONNECTION_REFUSED
193-119-48-13.static.tpgi.com.au:42000/' failed: Error in connection establishment: net::ERR_CONNECTION_REFUSED
193-119-48-13.static.tpgi.com.au:444/' failed: Error in connection establishment: net::ERR_CONNECTION_REFUSED
193-119-48-13.static.tpgi.com.au:80/' failed: Error in connection establishment: net::ERR_SSL_PROTOCOL_ERROR
193-119-48-13.static.tpgi.com.au:81/' failed: Error in connection establishment: net::ERR_CONNECTION_REFUSED
bitbucket.com/' failed: Error during WebSocket handshake: Unexpected response code: 301
bitbucket.com:55555/' failed: WebSocket opening handshake timed out
bitbucket.com:80/' failed: Error in connection establishment: net::ERR_CONNECTION_CLOSED
github.com/' failed: Error during WebSocket handshake: Unexpected response code: 200
github.com:55555/' failed: Error in connection establishment: net::ERR_CONNECTION_TIMED_OUT
github.com:80/' failed: Error in connection establishment: net::ERR_SSL_PROTOCOL_ERROR
mbohun.github.io/' failed: Error during WebSocket handshake: Unexpected response code: 200
mbohun.github.io:42424/' failed: WebSocket opening handshake timed out
mbohun.github.io:80/' failed: WebSocket opening handshake timed out
```
