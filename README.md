Transfer
Description: Script made by aniket & also free for use
Usage: transfer [flags] or transfer [flag] [args] or transfer [filePathToUpload]
  -d  Download a single file
      First arg: Output file directory
      Second arg: File url id
      Third arg: File name
  -o  Onetime file upload  
  -h  Show the help
  -v  Get the tool version
Examples:
  ./file-merchant /root/Desktop/fileToTransfer.txt
  ./file-merchant /firstFileToTransfer.txt ~/secondFileToTransfer.txt ~/thirdFileToTransfer.txt
  ./file-merchant -d ~/outputDirectory fileID fileName
  ./file-merchant -o ~/fileToTransfer.txt# file-merchant
