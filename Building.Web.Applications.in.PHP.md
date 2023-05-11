# Building Web Applications in PHP

   **author**: `MHK`  
   **date**: `2023-05-11`  

<br><br><br>

- Certificate : [5 Grades](https://www.coursera.org/learn/web-applications-php/home/assignments)
    1. **week 2** (*20%*) **:** `Assignment` **>** `HyperText Markup Language (HTML)` [:link:](https://www.coursera.org/learn/web-applications-php/supplement/xdWbT/assignment-specification-hypertext-markup-language-html)
    1. **week 5** (*20%*) **:** `Assignment` **>** `Our First PHP Application` [:link:](https://www.coursera.org/learn/web-applications-php/supplement/nVhOX/assignment-specification-our-first-php-application)
    1. **week 6** (*20%*) **:** `Assignment` **>** `Guessing Game` [:link:](https://www.coursera.org/learn/web-applications-php/gradedLti/2rxm3/auto-grader-guessing-game)
    1. **week 7** (*20%*) **:** `Assignment` **>** `Reversing an MD5 hash (password cracking)` [:link:](https://www.coursera.org/learn/web-applications-php/supplement/Hv6JI/assignment-specification-reversing-an-md5-hash-password-cracking)
    1. **week 8** (*20%*) **:** `Assignment` **>** `Rock Paper Scissors` [:link:](https://www.coursera.org/learn/web-applications-php/supplement/hmisw/assignment-specification-rock-paper-scissors)

<details>
<summary>Week 1</summary>

- **Lecture Materials** **>** Practice Quiz : *Request-Response*
    - When a browser connects to a web server to retrieve a document, what is the default TCP/IP port that is used?
        - `80`
    - When a browser connects to a web server to retrieve a document, what command is sent to the server?
        - `get`
    - Which of the HTTP headers does the browser look at to decide how to display the retrieved document?
        - [x] Content-type
    - What does the second "T" of HTTP stand for?
        - [x] Transfer
    - Which of the following is NOT part of a Uniform Resource Locator?
        - [x] Operating System
    - Which HTML tags typically generate a request to retrieve a document?
        - [x] a
        - [x] img
    - What standards organization publishes many of the documents that describe the protocols we use on the Internet?
        - [x] IETF


- **Assignment** **>** Request-Response Cycle

  |                |                                                  |
  |----------------|--------------------------------------------------|
  | Last-Modified  | `Sat, 13 May 2017 11:22:22 GMT`                  |
  | ETag           | `1d3-54f6609240717`                              |
  | Content-Length | `467`                                            |
  | Cache-Control  | `max-age=0, no-cache, no-store, must-revalidate` |
  | Content-Type   | `text/plain`                                     |

</details>

<details>
<summary>Week 2</summary>

- **Lecture Materials** **>** Practice Quiz : *HTML*
    - What is true about the following HTML?
        - [x] The reference is an absolute reference
    - What do you put at the beginning of an HTML file to inform the browser which variant of HTML you will be using in this document?
        - [x] DOCTYPE
    - What is the name of the tag that is used in a document's <head> area to set the text shown in the tab of the browser or title bar?
        - `title`
    - In HTML, what attribute is used to indicate text that will be shown if an image is not loaded or read to a user that is using a screen reader?
        - `alt`
    - For the following HTML:
        - [x] src
    - How do you show a less-than (<) in an an HTML page?
        - [x] &amp;lt;
    - What does the &lt;ul&gt; tag accomplish?
        - [x] Begins an unordered list
    - In a table, what is the general order of tags from outer to inner when constructing a table?
        - [x] &lt;table&gt; &lt;tr&gt; &lt;td&gt;


- **Assignment** **>** HyperText Markup Language (HTML)
    - replace `... Your Name xxxxxx ...` by yours
    ```html
    <!doctype html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <title> ... Your Name xxxxxx ... </title>
    </head>
    <body>
    <h1>A Header</h1>
    <p>
        These pages are intended to be explored in the
        developer console of your browser.
    </p>
    <p>
        A paragraph of text.
        Whatever line wrapping that is present in the
        file or lots
        of extra spaces in the file are generally ignored
        and the text is re-wrapped based on the width
        of browser.
    </p>
    <p>You can add a style like <strong>bold</strong>
        to some text by enclosing it in the <em>appropriate</em>
        tag.
    </p>
    <p>
        You can even mark some text so that it is a
        <a href="lists.htm">link to another page</a>.
    </p>
    <p>
    <pre>
    If you        use the pre tag
       The browser respects spaces
    and
    line
    ends
            and shows the text in a
            monospace font.
    
    
    
    </pre>
    <p>
        This material is part of the
        <a href="https://www.wa4e.com/" target="_blank">
            Web Applications for Everybody (WA4E)
        </a> website and is copyright Creative
        Commons Attribution. You are welcome to
        reuse and remix these examples for your
        own use with attribution.
        You can download a ZIP file of the
        <a href="../html.zip">source code</a>
        for these examples.
    </p>
    <span>span</span>
    <div>div</div>
    <ul>
        <li><strong>li 1</strong></li>
        <li><em>li 2</em></li>
        <li>li 3</li>
    </ul>
    </body>
    </html>
    ```

</details>

<details>
<summary>Week 3</summary>

- **Lecture Materials** **>** Practice Quiz : *CSS*
    - Which of the following is not a way to include CSS in an HTML page?
        - [x] Using the <font> tag to enclose other tags
    - Which HTML tag does nothing to the text it surrounds and has as its sole purpose to create a "handle" so as to be able to apply CSS to the text?
        - `span`
    - Why is there more than one font listed in the following CSS rule?
        - [x] They are listed in descending preference order if fonts are not present in the browser
    - Which CSS selector controls how a link (anchor tag) looks while the user mouses over the link (i.e. while hovering)?
        - `:hover`
    - Which of these CSS rules make text appear in a bold face font?
        - [x] font-weight: bold
    - What CSS selector would style a tag that looks like this: `< ... class="puppy">`
        - [x] .puppy { ...
    - What CSS rule allows you include a tag in markup but hide it from view in the browser?
        - [x] visibility: hidden;
    - Which of the following CSS selectors is between the content area and the border? (CSS box model)
        - [x] padding
    - What tag is used to import a style sheet into an HTML document?
        - `link`


- **Lecture Materials** **>** Cascading Style Sheets (CSS)
    - `blocks.css` :
      ```css
      /* This is a partial blocks.css, you need to add more rules
         to this file to complete the assignment.  Do not add any CSS
         styling to the original index.htm / start.htm */
      
      body {
          font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
          text-align: center;
          margin: 0;
          padding: 0;
      }
      
      /* Here is one of many  CSS rules you will need... */
      #one {
          border-style: solid;
          border-color: blue;
          border-width: 5px;
          padding: 5px;
          margin: 5px;
          width: 25%;
          position: fixed;
          z-index: 5;
          text-align: left;
          bottom: 0;
          right: 0;
      }
      
      #three {
          border-style: solid;
          border-color: darkorange;
          border-width: 5px;
          padding: 5px;
          margin: 5px;
          width: 25%;
          position: fixed;
          z-index: 5;
          text-align: left;
          top: 0;
          left: 0;
      }
      
      #two {
          border-style: solid;
          border-color: forestgreen;
          border-width: 5px;
          padding: 5px;
          margin: 5px;
          width: 25%;
          position: fixed;
          z-index: 5;
          text-align: left;
          top: 0;
          right: 0;
      }
      
      #four {
          border-style: solid;
          border-color: yellow;
          border-width: 5px;
          padding: 5px;
          margin: 5px;
          width: 25%;
          position: fixed;
          z-index: 5;
          text-align: left;
          bottom: 0;
          left: 0;
      }
      
      #link {
          width: 50%;
          display: inline-block;
          margin: 0;
      }
      
      #link a {
          display: inline-block;
          background-color: #4663cd;
          color: #fefefe;
          padding: 5px 3px;
          font-size: 14px;
          line-height: 20px;
          text-decoration: none;
          text-shadow: 0 1px 0 #3c58c7;
          font-weight: 500;
      }    
      ```

</details>

<!--<details>
<summary>Week 4</summary>

screen shots
</details>-->

<details>
<summary>Week 5</summary>

- **Lecture Materials** **>** Practice Quiz : *PHP*
    - ########### ToDo ##############

- #### ASCII ART:

<details>
<summary>A</summary>

```html
<span>
    AAAAA
    A   A
    AAAAA
    A   A
    A   A
</span>
```

</details>
<details>
<summary>B</summary>

```html
<span>
    BBBBB
    B   B
    BBBBB
    B   B
    BBBBB
</span>
```

</details>
<details>
<summary>C</summary>

```html
<span>
    CCCCC
    C
    C
    C
    CCCCC
</span>
```

</details>
<details>
<summary>D</summary>

```html
<span>
    DDDD
    D   D
    D   D
    D   D
    DDDD
</span>
```

</details>
<details>
<summary>E</summary>

```html
<span>
    EEEEE
    E
    EEEE
    E
    EEEEE
</span>
```

</details>
<details>
<summary>F</summary>

```html
<span>
    FFFFF
    F
    FFF
    F
    F
</span>
```

</details>
<details>
<summary>G</summary>

```html
<span>
    GGGGG
    G
    G  GG
    G   G
    GGGGG
</span>
```

</details>
<details>
<summary>H</summary>

```html
<span>
    H   H
    H   H
    HHHHH
    H   H
    H   H
</span>
```

</details>
<details>
<summary>I</summary>

```html
<span>
    IIIII
     I
     I
     I
    IIIII
</span>
```

</details>
<details>
<summary>J</summary>

```html
<span>
    JJJJJ
      J
      J
    J J
     JJ
</span>
```

</details>
<details>
<summary>K</summary>

```html
<span>
    K   K
    K  K
    KKK
    K  K
    K   K
</span>
```

</details>
<details>
<summary>L</summary>

```html
<span>
    L
    L
    L
    L
    LLLLL
</span>
```

</details>
<details>
<summary>M</summary>

```html
<span>
    M     M
    MM   MM
    M M M M
    M  M  M
    M     M
</span>
```

</details>
<details>
<summary>N</summary>

```html
<span>
    N     N
    NN    N
    N N   N
    N  N  N
    N   N N
</span>
```

</details>
<details>
<summary>O</summary>

```html
<span>
    OOOOO
    O   O
    O   O
    O   O
    OOOOO
</span>
```

</details>
<details>
<summary>P</summary>

```html
<span>
    PPPPP
    P   P
    PPPPP
    P
    P
</span>
```

</details>
<details>
<summary>Q</summary>

```html
<span>
    QQQQQ
    Q   Q
    Q   Q
    Q  QQ
    QQQQQQ
</span>
```

</details>
<details>
<summary>R</summary>

```html
<span>
    RRRRR
    R   R
    RRRRR
    R R
    R  R
</span>
```

</details>
<details>
<summary>S</summary>

```html
<span>
    SSSSS
    S
    SSSSS
        S
    SSSSS
</span>
```

</details>
<details>
<summary>T</summary>

```html
<span>
    TTTTTT
      T
      T
      T
      T
</span>
```

</details>
<details>
<summary>U</summary>

```html
<span>
    U   U
    U   U
    U   U
    U   U
    UUUUU
</span>
```

</details>
<details>
<summary>V</summary>

```html
<span>
    V   V
    V   V
    V   V
     V V
      V
</span>
```

</details>
<details>
<summary>W</summary>

```html
<span>
    W   W
    W   W
    W W W
    WW WW
    W   W
</span>
```

</details>
<details>
<summary>X</summary>

```html
<span>
    X   X
     X X
      X
     X X
    X   X
</span>
```

</details>
<details>
<summary>Y</summary>

```html
<span>
    Y   Y
     Y Y
      Y
      Y
      Y
</span>
```

</details>
<details>
<summary>Z</summary>

```html
<span>
    ZZZZZ
        Z
      Z
    Z
    ZZZZZ
</span>
```

</details>

- **Assignment** **>** Our First PHP Application
    - replace `Your Name` by yours
    - replace `........` by *ASCII ART* of first caracter of **your name** from the above list
      ```php
      <!DOCTYPE html>
      <html>
      <head>
      <title>Your Name PHP</title>
      </head>
      <body>
      <h1>Your Name PHP</h1>
      <p>The SHA256 hash of "Your Name" is
      <?php echo hash('sha256', 'Your Name'); ?></p>
      <pre>
      ASCII ART:
      
      .......... ... ....... ... ....... ... ....... ... .......
      .......... ... ....... ... ....... ... ....... ... .......
      .......... ... ....... ... ....... ... ....... ... .......
      .......... ... ....... ... ....... ... ....... ... .......
      .......... ... ....... ... ....... ... ....... ... .......
      </pre>
      <a href="check.php">Click here to check the error setting</a>
      <br/>
      <a href="fail.php">Click here to cause a traceback</a>
      </body>
      ```

</details>

<details>
<summary>Week 6</summary>

- **Lecture Materials** **>** Practice Quiz : *PHP Arrays*
    - ########### ToDo ##############


- **Assignment** **>** Guessing Game
    - replace `Your Name` by yours
    - replace `99` by your test number
    ```php
    <html>
    <head>
        <title>Guessing Game for Your Name</title>
    </head>
    <body>
    <h1>Welcome to my guessing game</h1>
    <p>
        <?php
        if (!isset($_GET['guess'])) {
            echo("Missing guess parameter");
        } else if (strlen($_GET['guess']) < 1) {
            echo("Your guess is too short");
        } else if (!is_numeric($_GET['guess'])) {
            echo("Your guess is not a number");
        } else if ($_GET['guess'] < 99) {
            echo("Your guess is too low");
        } else if ($_GET['guess'] > 99) {
            echo("Your guess is too high");
        } else {
            echo("Congratulations - You are right");
        }
        ?>
    </p>
    </body>
    </html>
    - ``` 

</details>

<details>
<summary>Week 7</summary>

- **Lecture Materials** **>** Practice Quiz : *Functions*
    - Why should you use functions?
        - [x] Avoid repetitive code
        - [x] Break complex code into logical chunks
        - [x] Organize your code
    - Which keyword defines a new function?
        - [x] function
    - Return values are type-specific in php functions (a function only returns a value of a specified data type.)
        - [x] False
    - What output does the following code produce?
        ```php
       function double($val){ $val = $val * 2; return $val; } $val = 15; $dval = double($val); echo "Value = $val Doubled = $dval";
        ```
        - [x] Value = 15 Doubled = 30
    - Which keyword is used to use code from one php file into a different PHP file?
        - [x] include
    - Which function prints out the internal configuration capabilities of your particular PHP installation?
        - [x] phpinfo()
    - Adding an ampersand ( & ) to a function parameter indicates that you are using call by [_____] for that parameter.
        - `reference`
    - The keyword [_____] will expand the scope of a variable outside of its function.
        - `global`
    - The [_____] function is used to check if a function already exists or not.
        - `function_exists`
    - It is common to use uppercase and/or long names for global variables to avoid confusion or mistaken reuse.
        - [x] True


- **Assignment** **>** Reversing an MD5 hash (password cracking)
    - replace `Your Name` by yours
    ```php
    <!DOCTYPE html>
    <head><title>Your Name MD5 Cracker</title></head>
    <body>
    <h1>MD5 cracker</h1>
    <p>This application takes an MD5 hash
        of a two-character lower case string and
        attempts to hash all two-character combinations
        to determine the original two characters.</p>
    <pre>
    Debug Output:
    <?php
    $goodtext = "Not found";
    $try = null;
    // If there is no parameter, this code is all skipped
    if (isset($_GET['md5'])) {
        $time_pre = microtime(true);
        $md5 = trim($_GET['md5']);
        $txt = '0123456789';
        $show = 15;
        for ($i = 0; $i < strlen($txt); $i++) {
            $ch1 = $txt[$i];
            for ($j = 0; $j < strlen($txt); $j++) {
                $ch2 = $txt[$j];
                for ($k = 0; $k < strlen($txt); $k++) {
                    $ch3 = $txt[$k];
                    for ($l = 0; $l < strlen($txt); $l++) {
                        $ch4 = $txt[$l];
                        $try = "{$ch1}{$ch2}{$ch3}{$ch4}";
                        $check = hash('md5', $try);
                        if ($check == $md5) {
                            $goodtext = $try;
                            break;
                        }
                        if ($show > 0) {
                            print "$check $try\n";
                            $show = $show - 1;
                        }
                    }
                    if ($goodtext == $try) break;
                }
                if ($goodtext == $try) break;
            }
            if ($goodtext == $try) break;
        }
        $time_post = microtime(true);
        print "Elapsed time: ";
        print $time_post - $time_pre;
        print "\n";
    }
    ?>
    </pre>
    <!-- Use the very short syntax and call htmlentities() -->
    <p>Original Text: <?= htmlentities($goodtext); ?></p>
    <form>
        <input type="text" name="md5" size="60"/>
        <input type="submit" value="Crack MD5"/>
    </form>
    <ul>
        <li><a href="index.php">Reset</a></li>
        <li><a href="md5.php">MD5 Encoder</a></li>
        <li><a href="makecode.php">MD5 Code Maker</a></li>
    </ul>
    </body>
    </html>
    ```

</details>

<details>
<summary>Week 8</summary>

- **Lecture Materials** **>** Practice Quiz : *Forms*
    - ########### ToDo ##############


- **Assignment** **>** Rock Paper Scissors
    - replace `Your Name` by yours in the following files
    - login.php
        ```php
        <?php // Do not put any HTML above this line
      
        if ( isset($_POST['cancel'] ) ) {
            // Redirect the browser to game.php
            header("Location: index.php");
            return;
        }
      
        $salt = 'XyZzy12*_';
        $stored_hash = '1a52e17fa899cf40fb04cfc42e6352f1';  // Pw is php123
      
        $failure = false;  // If we have no POST data
      
        // Check to see if we have some POST data, if we do process it
        if ( isset($_POST['who']) && isset($_POST['pass']) ) {
            if ( strlen($_POST['who']) < 1 || strlen($_POST['pass']) < 1 ) {
                $failure = "User name and password are required";
            } else {
                $check = hash('md5', $salt.$_POST['pass']);
                if ( $check == $stored_hash ) {
                    // Redirect the browser to game.php
                    header("Location: game.php?name=".urlencode($_POST['who']));
                    return;
                } else {
                    $failure = "Incorrect password";
                }
            }
        }
      
        // Fall through into the View
        ?>
        <!DOCTYPE html>
        <html>
        <head>
        <?php require_once "bootstrap.php"; ?>
        <title>Your Name's Login Page</title>
        </head>
        <body>
        <div class="container">
        <h1>Please Log In</h1>
        <?php
        // Note triple not equals and think how badly double
        // not equals would work here...
        if ( $failure !== false ) {
            // Look closely at the use of single and double quotes
            echo('<p style="color: red;">'.htmlentities($failure)."</p>\n");
        }
        ?>
        <form method="POST">
        <label for="nam">User Name</label>
        <input type="text" name="who" id="nam"><br/>
        <label for="id_1723">Password</label>
        <input type="text" name="pass" id="id_1723"><br/>
        <input type="submit" value="Log In">
        <input type="submit" name="cancel" value="Cancel">
        </form>
        <p>
        For a password hint, view source and find a password hint
        in the HTML comments.
        <!-- Hint: The password is the three character name of the 
        programming language used in this class (all lower case)
        followed by 123. -->
        </p>
        </div>
        </body>      
        ```
    - game.php
        ```php
        <?php
          
        // Demand a GET parameter
        if (!isset($_GET['name']) || strlen($_GET['name']) < 1) {
            die('Name parameter missing');
        }
          
        // If the user requested logout go back to index.php
        if (isset($_POST['logout'])) {
            header('Location: index.php');
            return;
        }
          
        // Set up the values for the game...
        // 0 is Rock, 1 is Paper, and 2 is Scissors
        $names = array('Rock', 'Paper', 'Scissors');
        const Rock = 0, Paper = 1, Scissors = 2, Test = 3;
        $human = isset($_POST["human"]) ? $_POST['human'] + 0 : -1;
          
        //$computer = 0; // Hard code the computer to rock
        // TODO: Make the computer be random
        $computer = array_rand([Rock, Paper, Scissors]);
          
        // This function takes as its input the computer and human play
        // and returns "Tie", "You Lose", "You Win" depending on play
        // where "You" is the human being addressed by the computer
        function check($computer, $human)
        {
            // For now this is a rock-savant checking function
            // TODO: Fix this
            switch (True) {
                case $human == $computer:
                    return 'Tie';
                case $human == Paper and $computer == Rock:
                case $human == Scissors and $computer == Paper:
                case $human == Rock and $computer == Scissors:
                    return 'You Win';
                case $human == Scissors and $computer == Rock:
                case $human == Paper and $computer == Scissors:
                case $human == Rock and $computer == Paper:
                    return 'You Lose';
            }
            return false;
        }
          
        // Check to see how the play happened
        $result = check($computer, $human);
          
        ?>
        <!DOCTYPE html>
        <html>
        <head>
            <title>Your Name's Rock, Paper, Scissors Game</title>
            <?php require_once "bootstrap.php"; ?>
        </head>
        <body>
        <div class="container">
            <h1>Rock Paper Scissors</h1>
            <?php
            if (isset($_REQUEST['name'])) {
                echo "<p>Welcome: ";
                echo htmlentities($_REQUEST['name']);
                echo "</p>\n";
            }
            ?>
            <form method="post">
                <select name="human">
                    <option value="-1">Select</option>
                    <option value="<?= Rock ?>">Rock</option>
                    <option value="<?= Paper ?>">Paper</option>
                    <option value="<?= Scissors ?>">Scissors</option>
                    <option value="<?= Test ?>">Test</option>
                </select>
                <input type="submit" value="Play">
                <input type="submit" name="logout" value="Logout">
            </form>
          
            <pre>
        <?php
        if ($human == -1) {
            print "Please select a strategy and press Play.\n";
        } else if ($human == Test) {
            for ($c = 0; $c < 3; $c++) {
                for ($h = 0; $h < 3; $h++) {
                    $r = check($c, $h);
                    print "Human=$names[$h] Computer=$names[$c] Result=$r\n";
                }
            }
        } else {
            print "Your Play=$names[$human] Computer Play=$names[$computer] Result=$result\n";
        }
        ?>
        </pre>
        </div>
        </body>
        </html>
        ```

</details>
