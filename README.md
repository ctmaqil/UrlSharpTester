# URL Sharp

URL Sharp is a simple bruteforce url tester that input ascending numbers in the url for testing. Current version: 2

## Usage

1. Run `URL TESTER cSharp.exe`
2. Enter Pre-Url Make sure the url includes `https://` or `http://`. 
> Example the Tested Url is https://google.com/{page-id}/index.php where {page-id} is to be tested.

```
> Enter Pre-Url: 
> https://google.com/
```

3. Enter End-Url
```
> Enter End-Url: 
> /index.php
```

4. Enter the Range that you want to test.
```
> Enter start range: 
> 1
> Enter last range: 
> 5
```

5. Url will be tested and result will be shown on console and exported to the file. The file is would be name as `URLSharp [{start range}-{last range}].txt`.


## Results
| Code| Results|
| ------ | ------ |
| Invalid Range | You entered a invalid range. Range must be a whole integer. |
| Valid! | Url is valid with a working page. |
| Not Found! | Url page was not found or Url return 404 Not Found. |
| Error [1] | Url return an error code that is not 404 |
| Error [2]| Error occurred when testing the URL. |




## Credits
Coded by [CTMAQIL](https://ctmaqil.com/) 

Coded in C#
