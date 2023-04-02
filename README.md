  <h1>Project Name: Vishvam</h1>

  <h2>Description</h2>
  <p>Vishvam is a web application that allows users to create their portfolio websites automatically. Users can fill out their information, select a theme and customize their portfolio website without writing any code. The application is built using Django, a Python web framework.</p>

  <h2>Requirements</h2>
  <ul>
    <li>Python 3.6 or higher</li>
    <li>Django 3.2 or higher</li>
  </ul>

  <h2>Installation</h2>
  <ol>
    <li>Clone the repository:</li>
  </ol>
  <pre><code>git clone https://github.com/bhatt-neel/Vishvam.git</code></pre>
  <ol start="2">
    <li>Navigate to the project directory:</li>
  </ol>
  <pre><code>cd Vishvam</code></pre>
  <ol start="3">
    <li>Create a virtual environment:</li>
  </ol>
  <pre><code>python3 -m venv env</code></pre>
  <ol start="4">
    <li>Activate the virtual environment:</li>
  </ol>
  <pre><code>source env/bin/activate</code></pre>
  <ol start="5">
    <li>Install the required packages:</li>
  </ol>
  <pre><code>pip install -r requirements.txt</code></pre>
  <ol start="6">
    <li>Create the database:</li>
  </ol>
  <pre><code>python manage.py migrate</code></pre>
  <ol start="7">
    <li>Run the development server:</li>
  </ol>
  <pre><code>python manage.py runserver</code></pre>

  <h2>Usage</h2>
  <ol>
    <li>Open a web browser and go to http://localhost:8000/</li>
    <li>Click on the "Sign up" link to create a new account.</li>
    <li>Fill out the registration form and click the "Register" button.</li>
    <li>After logging in, click on the "Create Portfolio" button.</li>
    <li>Fill out the form with your personal information and select a theme for your portfolio website.</li>
    <li>Click the "Create Portfolio" button to generate your portfolio website.</li>
    <li>You can view your portfolio website by clicking on the "View Portfolio" button.</li>
  </ol>

  <h2>Features</h2>
  <ul>
    <li>User authentication and registration</li>
    <li>Dynamic form fields for adding personal information</li>
    <li>Theme selection for customizing the portfolio website</li>
    <li>Automatic website generation using Django templates</li>
  </ul>

  <h2>Contributing</h2>
  <p>If you'd like to contribute to this project, please fork the repository and create a new branch for your feature or bug fix. Once you've made your changes, submit a pull request and we'll review it as soon as possible. We welcome all contributions and appreciate your help in making Portfolio Builder even better!
<h2>License</h2>
<p>Portfolio Builder is licensed under the MIT License. See the LICENSE file for more information.</p>
