<h1>Build a RAG in 10 minutes with Python, ChromaDB and OpenAI</h1>

<h2>Prerequisites</h2>
<ul>
  <li>Python 3.11+</li>
</ul>



<h3>2. Create a virtual environment</h3>

```
py -3.13 -m venv .venv
```

<h3>3. Activate the virtual environment</h3>

```
 .venv\Scripts\activate
```

<h3>4. Install libraries</h3>

```
 pip install -r requirements.txt --no-cache-dir
```

<h3>5. Add OpenAI API Key</h3>
Get an OpenAI API Key from here: https://platform.openai.com/settings/organization/admin-keys<BR>
Add it to .env.example<BR>
Rename to .env<BR>

<h2>Executing the scripts</h2>

- Open a terminal in VS Code

- Execute the following command:

```
python fill_db.py
python ask.py
```
