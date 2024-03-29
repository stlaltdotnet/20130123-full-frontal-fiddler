# 02 Session tabs

## Statistics

- performance timers
- response bytes (by content type)
    - response chart
- worldwise performance

## Inspectors

Divided into request/response (top/bottom)

### Request

- headers
- text and syntax views
- WebForms
- cookies
- raw
- JSON/XML

### Response

- transformer
- headers
- text and syntax views
- image view
- web view
- cookies
- raw
- JSON/XML

## AutoResponder

- enable automatic responses
- drag-and-drop responses (w/children)
- enable latency
- save/load responses

## Composer

- manually creating requests
- drag-and-drop requests

## FiddlerScript

(see 03-Fiddler-Script.md)

## Filters

- intra/internet zones
- host filter
- client process filter
- request header filter
- breakpoints
- response status codes
- response type and size
- response headers

## Log

Shows log messages from Fiddler and extensions

- set preference `fiddler.debug.extensions.showerrors` to show errors generated by extensions
- set preference `fiddler.debug.extensions.verbose` to write log messages and warnings to the log tab

## Timeline

- individual session timeline
- multiple selected sessions aggregate timeline
- context menu
    - auto-scale chart
    - client pipe map (each inbound connection/process)
    - server pipe map (each outbound connection from Fiddler/port)

## Using the "TextWizard" to compose strings that are painful to do by hand

- to/from base64
- to/from url encoding
- to/from JS string (auto-inserts escape sequences)
- to/from HTML encoding