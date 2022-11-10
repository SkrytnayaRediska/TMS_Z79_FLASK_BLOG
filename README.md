<h1>TO START:</h1>

<p>1. Install requirements:</p>
<pre><code>pip install flask
</code></pre>

<p>2. Create database. RUN THIS ONLY ONCE AT THE START!!! No need to do this every time you running the app</p>
<pre><code>python init_db.py
</code></pre>

<p>3. If you have smth like Linux:</p>
<pre><code>export FLASK_APP=blog
flask run
</code></pre>

If Windows:

1. add this in the end of blog.py<pre><code>app.run()
</code></pre>
2. go to the terminal and run: <pre><code>python blog.py
</code></pre>
