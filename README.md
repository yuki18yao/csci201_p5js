This is a skills assignment for CSCI201 class.
Our task was to learn how to create p5.js sketch and upload it to the giothub page. 

p5.js editor for this code: https://editor.p5js.org/yuki18yao/sketches/LClkviBzF

Link to the website: 
yuki1@DESKTOP-RADH5UJ MINGW64 ~
$ cd workspace/

yuki1@DESKTOP-RADH5UJ MINGW64 ~/workspace
$ ls
MyWork                       intro-curriculum-3001      node-js-http-3014
adding-up-1                  intro-curriculum-3002      node-js-http-3015
ajax-study-4008              intro-curriculum-3004      node-js-http-3016
amplifyapp                   intro-curriculum-3005      node-js-http-3017
aptos-core                   intro-curriculum-3006      nodejs-http
assessment                   intro-curriculum-3010      nodejs-study
assessment2                  intro-curriculum-3011      nodejs-study-2
async-io-problem             intro-curriculum-3017      os-command-injection
bot-study                    intro-curriculum-3020      password-challenger
bot-todo                     intro-curriculum-3027      pennapps-2023
chat_assistant               js-grammar                 portfolio
component-and-props          linux-study                practice-intro-4002
component-study              linux-study-2              projects
csrf-study                   meeting_minutes_generator  rdb-study
css-study                    my-wave-portal             react-hooks
damage-calc-4004             my_first_flutter           react-next-study
damage-calc-4005-gh-actions  my_portfolio               schedule-arranger
dom-manipulation-4007        nextjs-api                 schedule-arranger-4017
env                          nn-chat                    schedule-arranger-4018
express-api                  nn-chat-3021               schedule-arranger-4019
express-study                nn-chat-3022               schedule-arranger-4020
express-ts                   nn-chat-3023               schedule-arranger-4021
fibonacci-1                  nn-chat-3024               schedule-arranger-4022
flutter_projects             nn-chat-3025               schedule-arranger-4023
genuine                      nn-chat-3026               todo
genuine_ai                   nn-chat-3028               trusty
gif-portal-starter           nn-chat-3029               ts-intro
git-study                    nn-chat-3030               web-storage-study
git-study-2                  nn-chat-3031               web_page_summarizer
github-oauth                 nn-chat-db                 webpack-study-4006
hire_me_pls                  node-js-http-3012          websocket-study-4009
hubot-study                  node-js-http-3013          yarn-training-1

yuki1@DESKTOP-RADH5UJ MINGW64 ~/workspace
$ git remote add origin git@github.com:yuki18yao/csci201_p5js.git
fatal: not a git repository (or any of the parent directories): .git

yuki1@DESKTOP-RADH5UJ MINGW64 ~/workspace
$   git branch -M main
fatal: not a git repository (or any of the parent directories): .git

yuki1@DESKTOP-RADH5UJ MINGW64 ~/workspace
$ mkdir cdci201_p5js

yuki1@DESKTOP-RADH5UJ MINGW64 ~/workspace
$ rm cdci201_p5js/
rm: cannot remove 'cdci201_p5js/': Is a directory

yuki1@DESKTOP-RADH5UJ MINGW64 ~/workspace
$ rm -r cdci201_p5js/

yuki1@DESKTOP-RADH5UJ MINGW64 ~/workspace
$ mkdir csci201_p5js

yuki1@DESKTOP-RADH5UJ MINGW64 ~/workspace
$ ls
MyWork                       intro-curriculum-3001      node-js-http-3015
adding-up-1                  intro-curriculum-3002      node-js-http-3016
ajax-study-4008              intro-curriculum-3004      node-js-http-3017
amplifyapp                   intro-curriculum-3005      nodejs-http
aptos-core                   intro-curriculum-3006      nodejs-study
assessment                   intro-curriculum-3010      nodejs-study-2
assessment2                  intro-curriculum-3011      os-command-injection
async-io-problem             intro-curriculum-3017      password-challenger
bot-study                    intro-curriculum-3020      pennapps-2023
bot-todo                     intro-curriculum-3027      portfolio
chat_assistant               js-grammar                 practice-intro-4002
component-and-props          linux-study                projects
component-study              linux-study-2              rdb-study
csci201_p5js                 meeting_minutes_generator  react-hooks
csrf-study                   my-wave-portal             react-next-study
css-study                    my_first_flutter           schedule-arranger
damage-calc-4004             my_portfolio               schedule-arranger-4017
damage-calc-4005-gh-actions  nextjs-api                 schedule-arranger-4018
dom-manipulation-4007        nn-chat                    schedule-arranger-4019
env                          nn-chat-3021               schedule-arranger-4020
express-api                  nn-chat-3022               schedule-arranger-4021
express-study                nn-chat-3023               schedule-arranger-4022
express-ts                   nn-chat-3024               schedule-arranger-4023
fibonacci-1                  nn-chat-3025               todo
flutter_projects             nn-chat-3026               trusty
genuine                      nn-chat-3028               ts-intro
genuine_ai                   nn-chat-3029               web-storage-study
gif-portal-starter           nn-chat-3030               web_page_summarizer
git-study                    nn-chat-3031               webpack-study-4006
git-study-2                  nn-chat-db                 websocket-study-4009
github-oauth                 node-js-http-3012          yarn-training-1
hire_me_pls                  node-js-http-3013
hubot-study                  node-js-http-3014

yuki1@DESKTOP-RADH5UJ MINGW64 ~/workspace
$ cd csci201_p5js/

yuki1@DESKTOP-RADH5UJ MINGW64 ~/workspace/csci201_p5js
$ git init
Initialized empty Git repository in C:/Users/yuki1/workspace/csci201_p5js/.git/

yuki1@DESKTOP-RADH5UJ MINGW64 ~/workspace/csci201_p5js (main)
$ git remote add origin git@github.com:yuki18yao/csci201_p5js.git

yuki1@DESKTOP-RADH5UJ MINGW64 ~/workspace/csci201_p5js (main)
$ touch README.md

yuki1@DESKTOP-RADH5UJ MINGW64 ~/workspace/csci201_p5js (main)
$ vim README.md

yuki1@DESKTOP-RADH5UJ MINGW64 ~
$ cd workspace/

yuki1@DESKTOP-RADH5UJ MINGW64 ~/workspace
$ ls
MyWork                       intro-curriculum-3001      node-js-http-3014
adding-up-1                  intro-curriculum-3002      node-js-http-3015
ajax-study-4008              intro-curriculum-3004      node-js-http-3016
amplifyapp                   intro-curriculum-3005      node-js-http-3017
aptos-core                   intro-curriculum-3006      nodejs-http
assessment                   intro-curriculum-3010      nodejs-study
assessment2                  intro-curriculum-3011      nodejs-study-2
async-io-problem             intro-curriculum-3017      os-command-injection
bot-study                    intro-curriculum-3020      password-challenger
bot-todo                     intro-curriculum-3027      pennapps-2023
chat_assistant               js-grammar                 portfolio
component-and-props          linux-study                practice-intro-4002
component-study              linux-study-2              projects
csrf-study                   meeting_minutes_generator  rdb-study
css-study                    my-wave-portal             react-hooks
damage-calc-4004             my_first_flutter           react-next-study
damage-calc-4005-gh-actions  my_portfolio               schedule-arranger
dom-manipulation-4007        nextjs-api                 schedule-arranger-4017
genuine_ai                   nn-chat-3029               web-storage-study
gif-portal-starter           nn-chat-3030               web_page_summarizer
git-study                    nn-chat-3031               webpack-study-4006
git-study-2                  nn-chat-db                 websocket-study-4009
github-oauth                 node-js-http-3012          yarn-training-1
hire_me_pls                  node-js-http-3013
hubot-study                  node-js-http-3014

yuki1@DESKTOP-RADH5UJ MINGW64 ~/workspace
$ cd csci201_p5js/

yuki1@DESKTOP-RADH5UJ MINGW64 ~/workspace/csci201_p5js
$ git init
Initialized empty Git repository in C:/Users/yuki1/workspace/csci201_p5js/.git/

yuki1@DESKTOP-RADH5UJ MINGW64 ~/workspace/csci201_p5js (main)
$ git remote add origin git@github.com:yuki18yao/csci201_p5js.git

yuki1@DESKTOP-RADH5UJ MINGW64 ~/workspace/csci201_p5js (main)
$ touch README.md

yuki1@DESKTOP-RADH5UJ MINGW64 ~/workspace/csci201_p5js (main)
$ vim README.md

yuki1@DESKTOP-RADH5UJ MINGW64 ~/workspace/csci201_p5js (main)
$ git add .
warning: LF will be replaced by CRLF in README.md.
The file will have its original line endings in your working directory

yuki1@DESKTOP-RADH5UJ MINGW64 ~/workspace/csci201_p5js (main)
$ git add .

yuki1@DESKTOP-RADH5UJ MINGW64 ~/workspace/csci201_p5js (main)
$ git commit -m "first commit"
[main (root-commit) 36e982f] first commit
 1 file changed, 1 insertion(+)
  create mode 100644 README.md

  yuki1@DESKTOP-RADH5UJ MINGW64 ~/workspace/csci201_p5js (main)
  $ git push -u origin main
  Enter passphrase for key '/c/Users/yuki1/.ssh/id_ed25519':
  Enumerating objects: 3, done.
  Counting objects: 100% (3/3), done.
  Writing objects: 100% (3/3), 255 bytes | 51.00 KiB/s, done.
  Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
  To github.com:yuki18yao/csci201_p5js.git
   * [new branch]      main -> main
   Branch 'main' set up to track remote branch 'main' from 'origin'.

   yuki1@DESKTOP-RADH5UJ MINGW64 ~/workspace/csci201_p5js (main)
   $ ls
   README.md  index.html  p5.js  p5.sound.min.js  sketch.js  style.css

   yuki1@DESKTOP-RADH5UJ MINGW64 ~/workspace/csci201_p5js (main)
   $ git add .
   warning: LF will be replaced by CRLF in index.html.
   The file will have its original line endings in your working directory
   warning: LF will be replaced by CRLF in p5.js.
   The file will have its original line endings in your working directory
   warning: LF will be replaced by CRLF in p5.sound.min.js.
   The file will have its original line endings in your working directory
   warning: LF will be replaced by CRLF in sketch.js.
   The file will have its original line endings in your working directory
   warning: LF will be replaced by CRLF in style.css.
   The file will have its original line endings in your working directory

   yuki1@DESKTOP-RADH5UJ MINGW64 ~/workspace/csci201_p5js (main)
   $ git add .

   yuki1@DESKTOP-RADH5UJ MINGW64 ~/workspace/csci201_p5js (main)
   $ git commit -m "Uploaded p5js files"
   [main 612b64f] Uploaded p5js files
    5 files changed, 121556 insertions(+)
     create mode 100644 index.html
      create mode 100644 p5.js
       create mode 100644 p5.sound.min.js
        create mode 100644 sketch.js
	 create mode 100644 style.css

	 yuki1@DESKTOP-RADH5UJ MINGW64 ~/workspace/csci201_p5js (main)
	 $ git push -u origin main
	 Enter passphrase for key '/c/Users/yuki1/.ssh/id_ed25519':
	 Enumerating objects: 8, done.
	 Counting objects: 100% (8/8), done.
	 Delta compression using up to 8 threads
	 Compressing objects: 100% (7/7), done.
	 Writing objects: 100% (7/7), 782.93 KiB | 2.34 MiB/s, done.
	 Total 7 (delta 0), reused 0 (delta 0), pack-reused 0
	 To github.com:yuki18yao/csci201_p5js.git
	    36e982f..612b64f  main -> main
	    Branch 'main' set up to track remote branch 'main' from 'origin'.

	    yuki1@DESKTOP-RADH5UJ MINGW64 ~/workspace/csci201_p5js (main)
	    $ vim README.md
	    This is a skills assignment for CSCI201 class.
	    Our task was to learn how to create p5.js sketch and upload it to the giothub pa
	    ge.

	    p5.js editor for this code: https://editor.p5js.org/yuki18yao/sketches/LClkviBzF



	    ~
	    ~
	    ~
	    ~
	    ~
	    ~
	    ~
	    ~
	    ~
	    ~
	    ~
	    ~
	    ~
	    ~
	    README.md[+] [unix] (19:11 04/12/2023)                                 6,0-1 All
	    "README.md" [unix] 7L, 217B written
	    [main 612b64f] Uploaded p5js files
	     5 files changed, 121556 insertions(+)
	      create mode 100644 index.html
	       create mode 100644 p5.js
	        create mode 100644 p5.sound.min.js
		 create mode 100644 sketch.js
		  create mode 100644 style.css

		  yuki1@DESKTOP-RADH5UJ MINGW64 ~/workspace/csci201_p5js (main)
		  $ git push -u origin main
		  Enter passphrase for key '/c/Users/yuki1/.ssh/id_ed25519':
		  Enumerating objects: 8, done.
		  Counting objects: 100% (8/8), done.
		  Delta compression using up to 8 threads
		  Compressing objects: 100% (7/7), done.
		  Writing objects: 100% (7/7), 782.93 KiB | 2.34 MiB/s, done.
		  Total 7 (delta 0), reused 0 (delta 0), pack-reused 0
		  To github.com:yuki18yao/csci201_p5js.git
		     36e982f..612b64f  main -> main
		     Branch 'main' set up to track remote branch 'main' from 'origin'.

		     yuki1@DESKTOP-RADH5UJ MINGW64 ~/workspace/csci201_p5js (main)
		     $ vim README.md

		     yuki1@DESKTOP-RADH5UJ MINGW64 ~/workspace/csci201_p5js (main)
		     $ git add .
		     warning: LF will be replaced by CRLF in README.md.
		     The file will have its original line endings in your working directory

		     yuki1@DESKTOP-RADH5UJ MINGW64 ~/workspace/csci201_p5js (main)
		     $ git add .

		     yuki1@DESKTOP-RADH5UJ MINGW64 ~/workspace/csci201_p5js (main)
		     $ git commit -m "Upldated README"
		     [main 87e3898] Upldated README
		      1 file changed, 7 insertions(+), 1 deletion(-)

		      yuki1@DESKTOP-RADH5UJ MINGW64 ~/workspace/csci201_p5js (main)
		      $ git push -u origin main
		      Enter passphrase for key '/c/Users/yuki1/.ssh/id_ed25519':
		      Enumerating objects: 5, done.
		      Counting objects: 100% (5/5), done.
		      Delta compression using up to 8 threads
		      Compressing objects: 100% (3/3), done.
		      Writing objects: 100% (3/3), 444 bytes | 111.00 KiB/s, done.
		      Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
		      remote: Resolving deltas: 100% (1/1), completed with 1 local object.
		      To github.com:yuki18yao/csci201_p5js.git
		         612b64f..87e3898  main -> main
			 Branch 'main' set up to track remote branch 'main' from 'origin'.

			 yuki1@DESKTOP-RADH5UJ MINGW64 ~/works
			 $ vim README.md
			 This is a skills assignment for CSCI201 class.
			 Our task was to learn how to create p5.js sketch and upload it to the giothub pa
			 https://yuki18yao.github.io/csci201_p5js/



Link to the website: https://yuki18yao.github.io/csci201_p5js/
