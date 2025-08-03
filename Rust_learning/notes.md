1] cargo - npm 
2] macros 
  - 
3] #[allow(unused_imports)] - don't show warning , if not used yet 

4] bind - built in static method  on the tcp struct  , part of the standard library 
5] :: v/s . 
6] 
.unwrap()
bind(...) returns a Result<T, E> — meaning: it might succeed or fail

.unwrap() says:

"Give me the TcpListener if successful, or crash the program if there’s an error"

Java equivalent: try { ... } catch (IOException e) { crash }
But shorter.
eq : ServerSocket listener = new ServerSocket(4221);

1. Http-server
   A] Responding with a response 200 on recieving a get response on our server . 
    
   An HTTP response is made up of three parts, each separated by a CRLF (\r\n):
  crlf -> CR and LF are control characters or bytecode that can be used to mark a line break in a text file.
  'https://developer.mozilla.org/en-US/docs/Glossary/CRLF'

  "End this line and start a new one.”


Status line.
Zero or more headers, each ending with a CRLF.
Optional response body. 
