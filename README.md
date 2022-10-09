The Lexical Analyzer checks the program's entire source code. One by one, it recognizes each token. Scanners are typically only introduced as needed by a parser to generate tokens. So firstly, it will get the next token by providing a 'Get next token' command to the lexical analyzer from the parser. Then the lexical analyzer searches the input until it detects the next token upon obtaining this instruction. And, then it returns the Parser token. 
When generating these tokens, the Lexical Analyzer skips white spaces and notes. If there is an error, the Lexical Analyzer compares the error to the source file and line number. Lexical Analyzer work in such a way as mentioned in the below steps.
 	Tokenization.
 	Give error messages.
 	Eliminate comments and white spaces.

