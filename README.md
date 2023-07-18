# image-lambda

Our main use for code is to add a photo in s3 and it will appear in images.json, which you can open it in new tab, the next images describe the happens:

[json-link](https://simpleimage214.s3.us-east-1.amazonaws.com/images.json?response-content-disposition=inline&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaDGV1LWNlbnRyYWwtMSJHMEUCIQCHZ5Xe1pypyRdusYJvvmZbjKzf84TYVIobpD537w0J6AIgGE9%2FhvGV3Mr3h4p4yJS71jL1G5%2BOQEyV%2B2ThEH2vIwIq6gIIchAAGgwzNTA2MTU1MzA1OTkiDDjvEdfYgZNfqsY%2F9yrHAj0K13P51TaFMYyw3N2htNDYRmW9m0xgvQatTvugwTdFWiSrQl2hvZlZLffTc9Ox1CKahhlr97dqavO6BvHG2MH%2BB6JG58fT%2BPL0djQ%2BhDSpasNbLTY8%2BjmkMHuaI9uFIU%2BKjM9br9dqn6%2F941M8WCf%2F5f%2FpZavJtaKzUCtSdlh3HEQ9OEJPiRlQduLz9eh6EP1DUrE6LBxNvOOtjP9JQakfnF1NP1NHfNj%2BrlPx%2BN6VVznC0c5nscvYdGgHe0OkU4Xr86LqzcolEq46PLWfU08jws1rF6l1P12LYCq9gwuwCl81AHRWgeYDS0cA%2BpAlUSTmwavmeqT7%2Bua9kug1xBiYMeZRjEZ7puxtpC2ABCcyZhdt8aOIDlZxYh%2FPV9YjHBjID3XZoxY7zUtrFy6uqa399ZXmEFhn7RXQlXafERGmvTUPOhWx4TCDj9mlBjqHAvv7pNaD%2BgChLi5wVBvnAqrPOqbNZfGy5wFbjiSPEFDeOuWBfWDf6qRKExkdkOLeeik6UVUJgfAt%2FuMyVZ%2BAzJGEjcTEGlkTEY%2Bl0AzjXElYPRM9APew9eXlZ0K%2BfDAXaCGtkKjR%2BKs8sQK1ucEl0MwWyR9Nq%2Bp6Uv%2BTaJBi61si2X3cCB4TQ%2BLJrff%2FYVkHJgLaaeoXITxE3kOBH9jSec3hd5ArGb%2Bpl6%2Bm5Wnp4egCNoPO6DgrXvVdQjnIsmwZKfug2WdX%2BWFqA5rgc1DAQT6qPCeU92eMmWvHiKgmlxBYYeHj3IY9usbRd0DDVgo%2BUxjBiadioFMPHgeSlJNsjjtIRzHaLs4i&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20230718T105502Z&X-Amz-SignedHeaders=host&X-Amz-Expires=299&X-Amz-Credential=ASIAVDISQNRT36ETR76N%2F20230718%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=da48e2fa08fee780086b65d1956ab3721ba26f4891e32662f2aef4efba94fb30)

![s3Look](./s3look.jpg)
![attachs](./lab17s3attachlambda.jpg)
## json look:
![jsonLook](./lab17jsonimg.jpg)
## test in lambda
![test](./testlab17.jpg)

## Issues you encountered during deployment of this lambda:
- accessing the images.json from lambda 
- size with modulas was more than 10mb 
- editing the permissions
- some picture wasn't working properly due to type, solving it with changing the type
