

// MY GUIDE TO HELP YOU USE MY JAVASCRIPT BATTLE SYSTEM IN YOUR GAME




STEP ONE.) KNOW EVERY FACTOR OF WHAT YOU'RE TOUCHING



		CLASSES, ID'S, VARIABLES, CLICK EVENTS, JQUERY EVENTS, ETC.



		BEFORE YOU TOUCH ANYTHING, READ INSIDE THE FUNCTIONS AND VARIABLES FILES, AND EXPLORE THE CODE, SO THAT YOU'LL KNOW

		IF YOU'RE GOING TO MESS EVERYTHING UP!!!



STEP TWO.) KNOW THE LANGUAGES!!!


		DO YOU UNDERSTAND HOW HTML AND CSS WORK?  GREAT, I FIGURED YOU WOULD IF YOU'RE GOING TO BUILD A GAME! BUT...

		function DO YOU KNOW JAVASCRIPT AND JQUERY?() {  IF (ANSWER == false) {

												LEAVE AND FIND SOMEONE WHO DOES;

											}		

											ELSE {

												PROCEED TO STEP 3;
											}

										});


STEP THREE.) OTHER ASSETS

			
			YOU NEED TO EITHER HAVE A PARTNER, OR YOURSELF, WHO'S ABLE TO WORK WITH BOTH A SERVER-SIDE LANGUAGE LIKE PHP/RUBY/PYTHON,

			AND KNOWS HOW TO WORK WITH SQL'S.  IF YOU WANT CHARACTER PROGRESSION, USER ACCOUNTS, AND JUST A DYNAMIC PERSONAL FEEL, 

			YOU WILL NEED A BACK-END.


STEP FOUR.) HEALTH, STRENGTH AND DEFENSE VALUES

			
			DO NOT LEAVE IT LIKE IT IS RIGHT NOW.  THEY'RE PRE-DETERMINED VALUES THAT CAN CHANGE BASED ON SWORD SELECTION

			I DID THIS FOR DEMONSTRATION PURPOSES BECAUSE I'M NOT BUILDING A WEB GAME OUT OF THIS.  IF ANYTHING, SET THEM TO EQUAL 0,

			AND THEN ADD A FUNCTION THAT CHANGES IT BASED ON 1.) CHARACTERS LEVEL PULLED FROM THE DATABASE, AND 2.) SIMILAR TO WHAT I 

			HAVE GOING RIGHT NOW, THEIR WEAPONS AND ARMOR.



			INCREASE STRENGTH AND DEFENSE VALUE LIMITS ---- AKA COPY PASTE THE IF ELSE STATEMENTS

			THE EQUATION FOR THE ATTACK ISNT SUPERB BUT WILL BE MUCH BETTER WITH A LARGER RANGE OF DEFENSE AND STRENGTH!!!




STEP FIVE.) SPELLS AND ABILITIES

			
			ONCE AGAIN, DO NOT LEAVE IT LIKE IT IS RIGHT NOW.  SIMILAR TO THE LAST POINT, UTILIZE YOUR DATABASE.  SET UP AN OPENING FUNCTION

			WHERE IF THE DATABASE CLAIMS THE CHARACTER HAS UNLOCKED THE ABILITY, THEN THE DISPLAY OF THAT ABILITY = TRUE.  LIKE,

			IF ($Play1FireSpell1Unlock == true) {

				// CODE THAT TELLS IT TO DISPLAY IN THE MENU LIKE: $(".//TableRowsClass//").html("<button id="P2FS1" class="firespell P2Ab" onclick="Play2FireSpell1()">Fire 1</button>")

			}

			else ......


			DOES THIS MAKE SENSE?  IF NOT, YOU NEED ANOTHER JAVASCRIPT MEMBER ON YOUR TEAM TO HELP!!!


STEP SIX.)  ADD MORE FACTORS!!!!


			1.)  WHAT DETERMINES HEALTH?  WHAT DETERMINES MANA?  DO THEY JUST INCREASE BY LEVEL?  OR IS THIS SOME SORT OF MONSTER

			ARENA GAME WHERE EACH MONSTER HAS PRESETS OF HP AND MP, AND DO THOSE PRESETS INCREASE BY LEVEL?  MY GOSH SO MANY OPTIONS OF 

			WHAT TO DO!!!  ONCE AGAIN, USE A DATABASE AND SERVER LANGUAGE FOR THIS!!!


			2.)  ADD THINGS LIKE MAGIC POWER AND MAGIC DEFENSE.  DON'T KEEP IT SO THAT FIRE 1 DOES 400 DAMAGE, MAKE IT SO FIRE 1 DOES

			DAMAGE BASED ON YOUR MAGIC POWER BUT DOES LESS BASED ON ENEMY MAGIC DEFENSE!!! (AND GIVE THEM COOL NAMES TOO, SERIOUSLY!)

			USE THE SAME MATHEMATICAL EQUATIONS I USED FOR ATTACK DAMAGE AS WELL FOR YOUR MAGIC DAMAGE.  WHOLE NUMBER ATTACKS THAT ARE 

			PRE-DETERMINED AREN'T VERY PROFESSIONAL OR FUN!!!


			3.)  MORE WEAPONS!!!  MORE ARMOR!!!  CURRENCY!!!  ADD IT ALL!!!!

			FOR WEAPONS AND ARMOR, I WOULD PERSONALLY SET IT TO BE BOTH EQUIPABLE IF YOU'RE GREATER THAN OR EQUAL THAN WEAPON LEVEL,

			AS WELL AS MAKE THEM INCREASE DAMAGE BY ___%, MAYBE ADD AN ABILITY TO CERTAIN ONES, OR EVEN....STATUS AILMENTS!


			4.)  STATUS AILMENTS AND BUFFS

			BURNING, FROZEN (LOSE A TURN!), SLOW, HASTE, BLIND, LESS STRENGTH, MORE STRENGTH, LOWER DEFENSE, HIGHER DEFENSE... ETC

			STATUS AILMENTS ADD MORE STRATEGY AND FUN TO THE GAME!

			SUPER EASY TOO, DEPENDING ON WHAT VERSION I HAVE RELEASED, THEN THIS MIGHT ALREADY BE ADDED TO THE SYSTEM, BUT IF IT'S NOT,

			I'LL TELL YOU HOW RIGHT NOW!

			1.) COPY AND PASTE THE HOLY SHEILD FUNCTION, TWICE (PLAYER 1 PLAYER 2)

			2.) CREATE VARIABLE FOR THE BUFF OR AILMENT

			3.) SET IT TO FALSE ON THE TOP OF PAGE, SET IT TO TRUE INSIDE THE FUNCTION

			4.) CREATE FACTORS THAT DETERMINE HOW LONG THIS IS TRUE

			5.) SET WHAT IT DOES (maybe inside the attack function put: "If ($Play1StrBuff == true) {
																				$Play1StrVal = $Play1StrVal	+ ($Play1StrVal * 0.25)
																			}"

				THIS WOULD MAKE PLAYER ONES STRENGTH VALUE INCREASE BY 25%!!!!

			6.) BUILD SPELL BUTTON, ADD MANA COST, ETC ETC


STEP SEVEN.)  ADD IMAGES 

				WHETHER YOU WANT TO ADD ANIMATIONS OR NOT, ATLEAST ADD IMAGES!!!  MAYBE A STOCK PHOTO OF AN ANIMATED FACE JUST TO GIVE

				CHARACTERS A PERSONAL FEEL, AND PUT IT WITH THE HEALTH AND MANA!  SERIOSLY!!  MAKES A BIG DIFFERENCE!!!


				ABOVE AND BEYOND, YOU'D ADD IMAGES INTO THE BATTLEFIELD THAT THE TEXTS COMES IN ON, MAYBE SOME ANIMATIONS OF FIRE BALLS OR 

				SWORDS....UP TO YOU!!!

				MAYBE ADD NEW BACKGROUND IMAGES, COOL MENU IMAGES, ANYTHING AND EVERYTHING MAKES A HUUUUUGE DIFFERENCE!!!


STEP EIGHT.)  EMAIL amhigs98@gmail.com A LINK TO YOUR GAME!!!  OR IF YOU WANT SUGGESTIONS OR NEED HELP, I JUST MIGHT BE THERE TO HELP YOU!!

				ALSO WOULD LOVE TO GIVE YOUR GAME A TEST!!!  AS LONG AS YOU PUT MY CODE TO GOOD USE!  :)








							# THANK YOU FOR YOUR INTEREST IN MY JAVASCRIPT BATTLE SYSTEM !!!


				




