Basic project. Receives data from Riot Games API about players of game League of Legends. It gets as JSON from REST API. Then parses it and shows it to the user. It has cache system, so if user hasn't changed since last time he/she has been sought up, bring up data from database instead. This way it prevents overhead in API requests.

The project is responsive for small and regular screen sizes, mobiles on landscape and portrait. Works nicely without JavaScript but has some nice enhancement with it.

This is production result, so I haven't really minimized files (would remove all the comments that I've written).

Nothing really more to tell, other than if you want to run it you have to:
- Change MySQL connection information in `__sys/res/dbconn.php`
- Change URL that it points to `__sys` in `__sys/loader.php`

I couldn't host it, because by nature of this project, it requires quite some calculation and I couldn't find reliable hosting that would let it run for 30 seconds without cutting it off. Instead here are some screenshots:

- Intro page
- Player page with data
- JavaScript assisted transition
- Mobile horizontal player page
- Mobile vertical player page
