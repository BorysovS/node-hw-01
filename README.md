# Command Line Interface - Contacts App

The program allows adding, viewing, and deleting contacts as well as getting
information about a single contact. It works via the command line and stores
data in the `contacts.json` file.

## Installation

1. Clone the repository or download its archive and extract it.
2. Open the terminal in the program directory.
3. Run `npm install` command to install dependencies.

## Usage

To execute commands, use the following keys:

- `-a` or `--action` - a required parameter that specifies the type of operation
  (list, get, add, remove).
- `-i` or `--id` - an identifier of a contact.
- `-n` or `--name` - a name of a contact.
- `-e` or `--email` - an email of a contact.
- `-p` or `--phone` - a phone number of a contact.

### Viewing a List of Contacts

To display a list of contacts, run the following command:

```
node index.js -a list
```

[Example](https://monosnap.com/file/fWPb5CsjkQgsTyG2J0bNIvVLCHWsaO)

### Getting Information About a Single Contact

To get information about a single contact, run the following command, where
`<id>` is the identifier of the contact:

```
node index.js -a get -i <id>
```

[Example](https://monosnap.com/file/yOCdG4mqG6zuNrX0NRZWGmWsTTZKOs)

### Adding a New Contact

To add a new contact, run the following command, where `<name>` is the name of
the contact, `<email>` is the email of the contact, `<phone>` is the phone
number of the contact:

```
node index.js -a add -n <name> -e <email> -p <phone>
```

[Example](https://monosnap.com/file/54iwnhUtRIUJyeiWyE6EaZpIHPdM0f)

### Deleting a Contact

To remove a contact, run the following command, where `<id>` is the identifier
of the contact:

```
node index.js -a remove -i <id>
```

[Example](https://monosnap.com/file/ebOWQFBFQaQCantwJj3qeAV8A8jqnn)

## Example

![Example CLI ScreenShot](./image/ExampleCLI.png 'Example')
