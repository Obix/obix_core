<h2>Obix core repository (pr_obix)</h2>

<p>Welcome!</p>

<p>For general information about the <em>Obix programming language</em>, please visit <a href="http://www.rps-obix.com">www.rps-obix.com</a></p>

<p>This Git repository contains the source code of org.obix.obix_core, licensed under the terms of the <a href="http://www.gnu.org/licenses/agpl.html">GNU AFFERO GENERAL PUBLIC LICENSE (AGPL) version 3</a>.</p>

<p>You can:</p>
<ul>
  <li>Look at the source code</li>
  <li>Download the source code to your computer, using <a href="http://git-scm.com/">Git</a></li>
  <li>Make changes to the code and test them locally, using <a href="http://www.rps-obix.com/downloads/system/installation.html">Obix's development environment</a></li>
  <li>Use your changes in an application licensed under the terms of the <a href="http://www.gnu.org/licenses/agpl.html">GNU AFFERO GENERAL PUBLIC LICENSE (AGPL) version 3</a></li>
  <li>contribute patches, enhancements and new features to the open-source community, using <a href="http://git-scm.com/">Git</a></li>
</ul>

<p> To install and use this repository locally on your computer, proceed as follows:</p>

<ol>
  <li><a href="http://www.rps-obix.com/downloads/system/installation.html">Install Obix</a></li>

  <li>Create an Obix project with the name <code>obix_core</code>, as follows:
    <ul>
      <li>Open an operating system command window</li>
      <li>Go to any directory in which you want to create an Obix project</li>
      <li>Enter the following command which will create a new directory named <code>obix_core</code>:
        <ul>
          <li>
          	<code>obix create_project project_id:"obix_core" kind:"library"</code>
          </li>
        </ul>
      </li>
    </ul>
  </li>

  <li>Download, install and configure <a href="http://git-scm.com/">Git</a>. Refer to Git's documentation for detailed instructions.</li>

  <li>Download the source code from this online repository into a local repository on your computer, as follows:
    <ul>
      <li>Delete the content of your projects <code>work</code> directory. Don't delete the directory itself, just make it empty. The content will be replaced when the remote repository is downloaded.</li>
      <li>Open a Git command window (see Git instructions applying to your operating system)</li>
      <li>Go to the <code>work</code> subdirectory</li>
      <li>Type (including the space and dot at the end of line):<br />
        <code>git clone git@github.com:Obix/obix_core.git .</code>
      </li>
    </ul>
  </li>
</ol>

<p>You have now setup a working environment.</p>
<p> You can now modify the source code, then compile and build a new version, and test everything locally on your computer. For further information look at the <code>readme</code> file in your local root directory of project <code>obix_core</code> and refer to the documentation available at <a href="http://www.rps-obix.com">www.rps-obix.com</a></p>
<p>For further information about using the source code version control (for example to upload your changes), please refer to <a href="http://git-scm.com/">Git</a> and <a href="https://github.com/">Github</a>'s  documentation.</p>

<!--
<p>If you want to use your modified version of the Obix core in one of your applications then:</p>
<ul>
  <li>Modify the path to file <code>obix.oar</code> which is defined in file <code>work/obix/lib/file_list.txt</code> of your application</li>
  <li>Modify the path to file <code>obix.jar</code> which is defined in file <code>work/java/lib/file_list.txt</code> of your application</li>
</ul>
-->

<p>If you need further support then please send a message to 'info {at} rps-obix {dot} com'.</p>
