# wc-tool
A Python script for a custom wc command line terminal tool.

Allows the following options via command line terminal:
./mwc <-option> <filename>

Options:
  -c : Outputs number of bytes in the file
  -l : Outputs the number of lines
  -w : Outputs number of words 
  -m : Outputs Number of characters
  No option entered : Outputs -l -c -w , in the same order.

Also has the option to enter standard input from tty.
e.g. : cat <filename> | ./mwc <-option>
