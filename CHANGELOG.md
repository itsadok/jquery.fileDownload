<h2>jQuery File Download Changelog</h2>

<h4>04/10/2012 - 1.2.1</h4>
<ul>
    <li>The iframe used in the POST was accidentally visible, this has been fixed</li>
</ul>

<h4>04/09/2012 - 1.2.0</h4>
<ul>
    <li>Added ability to specify an <i>httpMethod</i> to perform the file download using. Useful for doing FORM submits that result in a file download</li>
    <li>Added <i>data</i> object which can be used with any <i>httpMethod</i> request to set parameters. This can be a key=value string or an object</li>
</ul>
<h4>04/09/2012 - 1.1.0</h4>
<ul>
    <li>Added new options arguments to make it very easy to pop up a jQuery Dialog, you just provide a "preparingMessageHtml" and/or "failMessageHtml"</li>
</ul>
<h4>03/22/2012 - 1.0.1</h4>
<ul>
    <li>Added more robust handling of certain kinds of file download errors in &lt; IE9. These versions of IE can disallow access to an iframe after an error has occured because the browser will display it's built in error page
        which exists in 'another domain' blocking JavaScript access to the iframe</li>
    <li>Switched iframe creation over to appendTo rather than append</li>
</ul>

<h4>03/21/2012 - 1.0.0</h4>
<ul>
    <li>Initial release</li>
</ul>