
 <img src="https://upload.wikimedia.org/wikipedia/commons/e/ee/PCPartPicker_Logo.png" width="50%">
 
# Price Notifier for PCPartPicker.com

- Console application that gives user periodic updates on price components from PCPartPicker.com using GET requests

## Issues

- No valid endpoints for PCPartPicker.com. Will not accept GET requests (403 responses). Program development incomplete, and ceased until workaround is found, or until official API is released. 

- Users welcome to use this similar application in the meantime: https://github.com/darrxh/Techping

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install dependencies before starting application.

```bash
pip install requests
pip install simpleaudio
```

## Usage
1. Unzip or clone repository onto machine.
2. Open a terminal or command line in resulting directory.
3. Type and Enter:
```bash
python main.py #or 'python3 main.py' depending on installation
```

4. Type and Enter:
```bash
add #to add component URLs from PCPartPicker. 
```

5. Type and Enter:

```bash
start #to start the checker.
```


- Type and Enter:

```bash
help #for more commands.
```



## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
MIT
