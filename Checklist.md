---


---

<h1 id="checklist-of-things-to-think-about--challenges-after-first-8-weeks">Checklist of things to think about &amp; challenges after first 8 weeks</h1>
<p>A checklist of things to look at and see if you can answer after the first eight weeks of the Founders And Coders curriculum.</p>
<p>This is <strong>long</strong> and somewhat difficult in places - you probably won’t be able to thoroughly look through all of it! Instead <strong>look at the things you think are most challenging first</strong></p>
<p>You should definitely not be concerned if you can’t answer everything yet - 8 weeks is not enough time to come to grips with it all!</p>
<p>Think of this as a learning aid to help you find the things you don’t understand, and then ask your fellow students/mentors on gitter! After the break maybe we can find a time to talk about it as a cohort to find things people struggle with.</p>
<p>It is roughly in order of when it was taught, but look at it in whichever order you choose.</p>
<p>For the challenges, I suggest you open a repo, and save them all there.</p>
<h2 id="contents">Contents</h2>
<ul>
<li><a href="#github">Github</a></li>
<li><a href="#javascript">Javascript</a></li>
<li><a href="#DOM-Manipulation">DOM Manipulation</a></li>
<li><a href="#HTML/CSS">HTML/CSS</a></li>
<li><a href="#HTTP">HTTP</a></li>
<li><a href="#callbacks">Callbacks</a></li>
<li><a href="#testing">Testing</a></li>
<li><a href="#node">node</a></li>
<li><a href="#databases">Databases</a></li>
<li><a href="#deploying">Deploying</a></li>
<li><a href="#auth">Auth</a></li>
<li><a href="#express">Express</a></li>
<li><a href="#handlebars">Handlebars</a></li>
<li><a href="#coding-best-practices">Coding Best Practices</a></li>
</ul>
<h3 id="github">Github</h3>
<ul>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> Why do we use github/git?</li>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled="">  What happens when you <code>clone</code> a repository?</li>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> What happens when you <code>fork</code> a repository?</li>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> What happens when we do <code>git pull origin master</code></li>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> How do we create a new branch on our local machine?</li>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> When we make a change to a file, how do we tell git to track it?</li>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> When we have finished working on a branch, how do we make sure that our changes do not cause a conflict with master? (this can all be done <strong>locally</strong>)</li>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> What does <code>git push origin [branch-name]</code> do?</li>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> Why do we make pull requests instead of just changing master directly?</li>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> Why is it important to run our team member’s branches when they make a pull request?</li>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> This is the working process you should follow, try to explain what happens at each step/why we do it:
<ul>
<li><code>git clone [repository]</code></li>
<li><code>git checkout -b new-feature</code><br>
<em>make some changes to index.js</em></li>
<li><code>git add index.js</code></li>
<li><code>git commit -m "added a cool new feature"</code><br>
<em>since we started, our partner has merged another branch into master</em></li>
<li><code>git checkout master</code></li>
<li><code>git pull origin master</code></li>
<li><code>git checkout new-feature</code></li>
<li><code>git merge master</code><br>
<em>merge conflict happens in index.js we fix it</em></li>
<li><code>git add index.js</code></li>
<li><code>git commit -m "fix merge conflict"</code></li>
<li><code>git push origin new-feature</code></li>
</ul>
</li>
</ul>
<h3 id="javascript">Javascript</h3>
<ul>
<li>Using
<ul>
<li><code>.map()</code></li>
<li><code>.filter()</code></li>
<li><code>.find()</code></li>
<li><code>.replace()</code></li>
<li><code>.reduce()</code></li>
<li><code>forEach()</code></li>
</ul>
</li>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> complete the challenges in comments <a href="https://gist.github.com/m4v15/08db7adb3856f7393672ded7a52f5e45">here</a></li>
</ul>
<h3 id="dom-manipulation">DOM Manipulation</h3>
<ul>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> What is DOM manipulation?</li>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> Try to write an HTML &amp; JS file that:
<ul>
<li>has a title, a text input and a button</li>
<li>when a user types something in the input, and clicks the button, it should change the title to what the user type</li>
<li>add another button to the html that will change the colour of the title</li>
</ul>
</li>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> Why should we always use <code>eventListeners</code> in Javascript and not inline <code>onClick</code> handlers in the HTML?</li>
</ul>
<h3 id="htmlcss">HTML/CSS</h3>
<ul>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> Why is accessibility important?</li>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> How do we test for accesbility?</li>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> What is semantic HTML?</li>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> Convert <a href="https://gist.github.com/m4v15/28d64be4fb3495aa1ff3a91bf4336bb1">the html linked here</a> to use semantic HTML instead of divs.</li>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> Using flexbox, change the layout of the above HTML to [something like this] <a href="https://www.figma.com/file/ewvTXphnscgQ2HD5gHkyHRz8/BASIC-DESGIN?node-id=0%3A1">https://www.figma.com/file/ewvTXphnscgQ2HD5gHkyHRz8/BASIC-DESGIN?node-id=0%3A1</a></li>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> You should use media queries to make it work for both desktop <em>and</em> mobile - without media queries, it should match the mobile design (i.e. be mobile first).</li>
</ul>
<h3 id="http">HTTP</h3>
<ul>
<li>What does the Status Code of an HTTP response tell us?</li>
<li>What are some common Status codes?</li>
<li>What are HTTP methods and what are the different methods intended for?</li>
</ul>
<h3 id="callbacks">Callbacks</h3>
<ul>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> Why should you use asynchronous forms of functions wherever possible in Node?</li>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> What are error-first callbacks, and why is it important to follow that pattern in your own code?</li>
<li>Take the following code:</li>
</ul>
<pre class=" language-js"><code class="prism  language-js">
<span class="token keyword">const</span> <span class="token function-variable function">getUsernameFromDatabase</span> <span class="token operator">=</span> <span class="token punctuation">(</span>email<span class="token punctuation">,</span> callback<span class="token punctuation">)</span> <span class="token operator">=&gt;</span> <span class="token punctuation">{</span>
  <span class="token keyword">const</span> database <span class="token operator">=</span> db<span class="token punctuation">.</span><span class="token keyword">get</span><span class="token punctuation">(</span><span class="token string">"data"</span><span class="token punctuation">)</span>
  <span class="token keyword">const</span> user <span class="token operator">=</span> database<span class="token punctuation">.</span><span class="token function">find</span><span class="token punctuation">(</span>user <span class="token operator">=&gt;</span> user<span class="token punctuation">.</span>email <span class="token operator">===</span> email<span class="token punctuation">)</span>
  <span class="token keyword">const</span> username <span class="token operator">=</span> user <span class="token operator">?</span> user<span class="token punctuation">.</span>username <span class="token punctuation">:</span> undefined
  <span class="token keyword">if</span> <span class="token punctuation">(</span><span class="token operator">!</span>username<span class="token punctuation">)</span><span class="token punctuation">{</span>
      <span class="token function">callback</span><span class="token punctuation">(</span><span class="token keyword">new</span> <span class="token class-name">Error</span><span class="token punctuation">(</span><span class="token string">'No user found'</span><span class="token punctuation">)</span><span class="token punctuation">)</span>
  <span class="token punctuation">}</span>
  <span class="token function">callback</span><span class="token punctuation">(</span><span class="token keyword">null</span><span class="token punctuation">,</span> username<span class="token punctuation">)</span>
<span class="token punctuation">}</span>
</code></pre>
<ul>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> Write a code which would call the above function and:
<ul>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> if there is an error, it should <code>console.log</code> to the user “Sorry there was a problem”</li>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> if it finds a user it should <code>console.log</code> to the user “Marhaba {username}!”</li>
</ul>
</li>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> Finish writing the below function so that when it inserts data into the database it uses the second argument as an <em>error first</em> callback. If the insert is successful it should send back <code>true</code> in the callback (remembering it is error first).</li>
</ul>
<pre class=" language-js"><code class="prism  language-js"><span class="token keyword">const</span> <span class="token function-variable function">addUser</span> <span class="token operator">=</span> <span class="token punctuation">(</span>data<span class="token punctuation">,</span> cb<span class="token punctuation">)</span> <span class="token operator">=&gt;</span> <span class="token punctuation">{</span>
    db_connection<span class="token punctuation">.</span><span class="token function">query</span><span class="token punctuation">(</span><span class="token string">'INSERT INTO users (name, email,password) VALUES ($1, $2, $3)'</span><span class="token punctuation">,</span> <span class="token punctuation">[</span>name<span class="token punctuation">,</span> email<span class="token punctuation">,</span> password<span class="token punctuation">]</span><span class="token punctuation">,</span> <span class="token punctuation">(</span>error<span class="token punctuation">)</span> <span class="token operator">=&gt;</span> <span class="token punctuation">{</span>
    <span class="token comment">// write your code here</span>
    <span class="token punctuation">}</span><span class="token punctuation">)</span>
<span class="token punctuation">}</span>
</code></pre>
<ul>
<li>Hard challenge! <a href="">Parrallel Functions</a></li>
</ul>
<h3 id="testing">Testing</h3>
<ul>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> <strong>WITHOUT writing the function itself,</strong> using tape, write tests for a function which can take two numbers, and a string. The string should be a mathematical operation: “add”, “subtract”, “times” or “divide”</li>
<li>The function should return the first number, then the mathematical operation of it combined with the second number:
<ul>
<li>(3, 2, “add”) should return 5</li>
<li>(3, 2, “subtract”) should return 1</li>
<li>(3, 2, “times”) should return 6</li>
<li>(3, 2, “divide”) should return 1.5</li>
<li>(2, 3, “subtract”) should return -1</li>
<li>(2, 3, “divide”) should return 0.667</li>
</ul>
</li>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> After writing some tests, try to write the function. Keep adding tests and developing the function until it can pass everything.</li>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> What is the difference between <code>equal</code> and <code>deepEqual</code> in testing?</li>
</ul>
<h3 id="node">Node</h3>
<ul>
<li class="task-list-item">
<p><input type="checkbox" class="task-list-item-checkbox" disabled=""> How do you initialise an <code>npm</code> or <code>node</code> project?</p>
</li>
<li class="task-list-item">
<p><input type="checkbox" class="task-list-item-checkbox" disabled=""> What is the only script that an <code>npm</code> project starts with, how do you add one?</p>
</li>
<li class="task-list-item">
<p><input type="checkbox" class="task-list-item-checkbox" disabled=""> What is the difference between <code>dependencies</code> and <code>devDependencies</code>?</p>
</li>
<li class="task-list-item">
<p><input type="checkbox" class="task-list-item-checkbox" disabled=""> What is the difference between package.json and package-lock.json</p>
</li>
<li class="task-list-item">
<p><input type="checkbox" class="task-list-item-checkbox" disabled=""> build a simple server that can:</p>
<ul>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> serve an html page with CSS and JS when you got to the <code>/</code> endpoint</li>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> when a user makes a request to <code>GET /students</code> return a JSON of all the FACK1 students</li>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> when a user makes a request <code>POST /students</code> with the data in the form <code>{name: 'Mavis'}</code> it returns plain text which says <code>Hello Mavis</code></li>
</ul>
</li>
<li class="task-list-item">
<p><input type="checkbox" class="task-list-item-checkbox" disabled=""> using supertest, test each of the routes on your server:</p>
<ul>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> check for status codes</li>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> check the body response is correct</li>
</ul>
</li>
<li class="task-list-item">
<p><input type="checkbox" class="task-list-item-checkbox" disabled=""> what is the difference between <code>querystring.parse</code> and <code>url.parse</code>?</p>
</li>
<li class="task-list-item">
<p><input type="checkbox" class="task-list-item-checkbox" disabled=""> what is the output from <code>querstring.stringify({search:'javascript'})</code> (hint: RUN THIS AND FIND OUT!)</p>
</li>
<li class="task-list-item">
<p><input type="checkbox" class="task-list-item-checkbox" disabled=""> what is the output from <code>url.parse('https://www.codewars.com/users/m4v15/completed')</code> (hint: RUN THIS AND FIND OUT!)</p>
</li>
<li>
<p>If I have the following file structure:</p>
</li>
</ul>
<pre><code>-public
  -index.html
  -index.js
  -index.css
-src
  -database
    -db_connect.js
  -app.js
  -server.js
</code></pre>
<ul>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> What file path should I use to <code>require</code> the <code>db_connect</code> file if I am in <code>app.js</code></li>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> What is the file path to <code>index.html</code> from <code>app.js</code></li>
</ul>
<h3 id="databases">Databases</h3>
<p>You should know:</p>
<ul>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> how to connect to a database using <code>node-postgres (pg)</code></li>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> how to build a database</li>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> why we use different database url’s for production, development and testing</li>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> If you have a <code>pg</code> database connection, <code>dbConnection</code> how do you use the <code>.query</code> method to query the database?
<ul>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> how should you pass in variables?</li>
</ul>
</li>
<li><strong>Challenge</strong>:
<ul>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> make a database of users and books, where each user can have multiple books and each book can be owned by multiple users (many to many)</li>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> write a small node script that will return the books of a particular user</li>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> you will need:
<ul>
<li>a SQL build script</li>
<li>a database connection javascript file</li>
<li>a database build javascript file</li>
<li>a config.env file</li>
<li>a app.js javascript file that has a function that takes a name of a user (a string) and queries the database, returning the name of the books that user has</li>
<li>Hint:
<ul>
<li>build script should have 3 tables: users (id, username, location), books (id, name), userbooks(user_id, book_id)</li>
</ul>
</li>
</ul>
</li>
</ul>
</li>
</ul>
<h3 id="deploying">Deploying</h3>
<ul>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> how to set up travis
<ul>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> How to make travis run your tests</li>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> How to make travis run something else (eg a linting script)</li>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> <strong>Bonus hard check</strong> how to make travis build it’s own database for testing on…</li>
</ul>
</li>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> How to set your app up on heroku
<ul>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> If your app heroku deploy doesn’t work, what can you do to find out the problem</li>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> How do you provision a database on heroku</li>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> How do you add environment variables on heroku</li>
</ul>
</li>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> What should we store in <code>config.env</code> file? Why?
<ul>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> Do the variable values in my <code>config.env</code> file have to be the same as their values on heroku?</li>
</ul>
</li>
</ul>
<h3 id="auth">Auth</h3>
<ul>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> how to hash and compare using bcrypt</li>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> how to save and read a cookie on the server</li>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> how to write a JWT on the server</li>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> why is a JWT secure?</li>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> how to secure a route and allow people with a good jwt through</li>
</ul>
<h3 id="express">Express</h3>
<ul>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> Convert the server from the node section to an express server. Try to use express router, and add a logger.</li>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> What is express middleware?</li>
</ul>
<h3 id="handlebars">Handlebars</h3>
<ul>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> Why can server side rendering be useful</li>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> What is handlebars?</li>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> Write a small express server that uses a handlebars template to render a user profile page, which show’s a user’s name, age, location and a list of hobbies, all of which should be passed into the template as <code>context</code>. Make endpoints on the server which uses this template for 5 different users (you need to make up the user data!)</li>
</ul>
<h3 id="coding-best-practices">Coding Best Practices</h3>
<ul>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> <strong>eslint</strong>
<ul>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> Why is linting important? Why should all of your code have the same style?</li>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> Install eslint on an old project of yours, and use the airbnb style guide. Try to fix all of the problems.</li>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> Now do the same but use the <code>standard</code> style guide - what’s the difference?</li>
</ul>
</li>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> <strong>Prettier</strong> set up prettier on your editor
<ul>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> set it to follow the rules in an eslint.config file if one is in the repo</li>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> set it to format on save</li>
</ul>
</li>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> how should you debug your code if things are going wrong? Give some different steps</li>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> You <strong>need</strong> to get very comfortable typing on an english keyboard with both hands. Having speed to try things out will help <strong>alot</strong> when you don’t understand things.</li>
</ul>

