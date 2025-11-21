# ICT414 Wireshark Practical Report

**Author:** Grace Daka

## 1. Overview

This report provides an analysis of HTTP traffic captured while
accessing the website **www.rocktv.app** using Wireshark.\
The objective was to identify the HTTP GET request, the corresponding
server response, and key network details such as client and server IP
addresses.

## 2. Steps Performed

1.  Started Wireshark with Administrator privileges.

2.  Selected the active network interface and initiated a live packet
    capture.

3.  Opened a web browser and navigated to: `http://www.rocktv.app

4.  Allowed the webpage to load and complete any redirects.

5.  Stopped the Wireshark capture.

6.  Applied display filter:

        http.host == "www.rocktv.app"

7.  Identified the HTTP GET request and corresponding HTTP response.

8.  Took a screenshot showing the filtered packets and detailed packet
    information.

9.  Saved the packet capture file as **ict414_capture.pcapng**.

## 3. Analysis Summary

-   **Client (Source) IP Address:** 192.168.1.218
-   **Server (Destination) IP Address:** 18.171.137.67
-   **URL Requested:** `http://www.rocktv.app/`
-   **HTTP Request Method:** GET\
-   **HTTP Response Code:** 396 (Redirect/Custom Response observed)

## 4. Conclusion

Wireshark successfully captured and filtered HTTP traffic for
**www.rocktv.app**.\
The GET request and server response were clearly identified, providing
insight into client-server communication over HTTP.
