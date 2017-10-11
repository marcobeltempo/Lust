# Groovy Git

**Description**: A simple Rust library containing the following four functions:

Function Name | Purpose | Usage | Output
-- | - | - | - 
getFileName(string FilePath)  | Consumes a string representing the absolute file path for a single file, returning only the file name | _getFileName("/home/dhpmuh/909SPD/FinalExam.exe")_ | _FinalExam.exe_
getFileSize(string FilePath)  | Consumes a string representing the absolute file path for a single file, returning the file size in bytes | _getFileSize("/home/dhpmuh/909SPD/FinalExam.exe")_ | _128 bytes_
generateSHA(string filePath) | Consumes a string representing the absolute file path for a single file, returning the calculated SHA1 hash | _generateSHA("The quick brown fox jumps over the lazy dog")_ |  _2fd4e1c..._
generateMD5 | Consumes a string representing the absolute file path for a single file, returning the calculated MD5 hash | _generateMD5("The quick brown fox jumps over the lazy dog")_ | _9e107d9d..._