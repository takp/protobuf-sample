# Protobuf-sample

This is sample code of Protocol Buffers based on [python tutorial](https://developers.google.com/protocol-buffers/docs/pythontutorial).

## Usage

- Write to output file 

```bash
$ python write.py output_file
output_file: Could not open file.  Creating a new one.
Enter person ID number: 111
Enter name: John
Enter email address (blank for none): john@example.com
Enter a phone number (or leave blank to finish): 001001001
Is this a mobile, home, or work phone? mobile
Enter a phone number (or leave blank to finish): 001001011
Is this a mobile, home, or work phone? work
Enter a phone number (or leave blank to finish): 
```

- Read output_file

```bash
$ python read.py output_file 
Person ID: 111
  Name: John
  E-mail address: john@example.com
  Mobile phone #: 
001001001
  Work phone #: 
001001011
```
