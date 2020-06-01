# WiFiManager_HtmlFile
This is a fork of [tzapu's WiFiManager](https://github.com/tzapu/WiFiManager)

The wifi.html and info.html files cannot contain newline charactor. It is also best to remove unnecessary whitespaces and newlines to reduce the file size for the limited flash space.
Easy way to achieve this is in a normal html file using any text editor with replace function:
1) replace all two whitespaces with one whitespace. "\s\s" to "\s"
2) do multiple runs of step 1) until all the whitespaces are single whitespace.
3) replace all newlines followed by a whitespace by nothing. "\n\s" to ""
4) replace all newlines by nothing. "\n" to ""

