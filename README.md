# GO-SLACK-AGE-BOT

Slack age bot using go.

## TO RUN/BUILD APP

 ```sh
 To Build the app:  go build
 To run the application : go run main.go
 ```
 
 ## To use the bot in Slack

Type below message in chat, in same workspace <br/>
@AgeBot my yob is "year"<br/>
eg : @AgeBot my yob is 1997<br/>
 ![image](https://user-images.githubusercontent.com/19289251/160975430-639fdaba-0145-46af-b137-f74b371e01a2.png)

## Technical Dependencies:

* Using godotenv for getting .env configs<br/>
* Using slacker for connecting and getting slack bot events & functionality <br/>
* To install godotenv:  go get github.com/joho/godotenv<br/>
* To install slacker : go get "github.com/shomali11/slacker"<br/>
* The application requires slack SLACK_BOT_TOKEN & SLACK_APP_TOKEN in the .env file, so create the .env file on root
* To get those credentials you'll need a slack account with a work space and you'll need to be the admin of that workspace
* Create a bot from scratch, give the nessecery permissions, enable socket mode and install the bot to workspace
* You'll then recive the oath token from oath and permisions when you install to workspace
* You can find the app token which is the socket token, from basic information tab

