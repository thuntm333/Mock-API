<h3>Introduction</h3>

<p>Mocking is basically faking, pretending, and there are many reasons that we testers might want to take advantage of this feature against APIs in Postman.</p>
  
<em>There are three main ways mocks can be created in Postman:</em>
<ul>
  <li><data>You can create a mock server that's based on a <strong>specification</strong> file. This is a really great option if you have the right documentation at hand, which details the API.</data></li>
  <li><data>You can create a mock server from <strong>scratch</strong>, adding in requests and telling Postman what response data to return.</data></li>
  <li><data>You can add a mock server to an <strong>existing Postman collection.</strong></data></li>
</ul>
Let's go ahead and do that, shall we?

<h3>Create and Run</h3>
<ol>
  <li>Left-click on the ellipsis menu here</li>
  <li>Choose Mock Collection to create Mock Server</li>
    <em>- Environment --> choose No Environment</em>
  <br>
    <em>- Ticked on Save the mock server URL as an new environment variables </em>
  <li>Press the ellipsis menu against the POST Auth and add an example.</li>
</ol>
<strong>If have more than 1 example, in header tab of API input</strong> <br><i>x-mock-response-name </i> in <strong>Key</strong> column <br> <i>Name's example</i> in <strong>Value</strong> column<br>
[image](https://github.com/user-attachments/assets/6e3b2c52-bc24-4e19-8f40-c5e0d4d81d12)
</body>
</html>

