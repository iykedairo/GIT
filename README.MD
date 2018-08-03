<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8" />
<meta http-equiv="X-UA-Compatible" content="IE=edge">

<style>
  body{
    background-color: #123123;
  }
</style>
</head>
<body>
<div>

  
<h1>STEPS TO GIT ON THE COMMAND LINE</h1>
 <small><i>Whether you want to contribute to an existing project or you want to set up a new one, these basic steps will get you covered. </i></small>
<ol>
  <li><h2>Clone A Branch</h2></li>
  <ul>
    <li><code>git clone -b branch-name https://github.com/user/repo.git</code></li>
    <li><code>cd repo #That's change into the newly created repo</code></li>
    <li><code>git rm -rf . #If you'd lie to clean up and start afresh, that's the code</code></li>
    <li>git checkout --orphan you-new-branch-name or git checkout -b new-branch-name</li>
    <small>Then create files and add them there</small>
    <li><code>git add -A #Git stage all files and folders in this directory</code></li>
    <li><code>git commit -a -m "Real good message about the upload"</code></li>
    <li><code>git push origin branch-name:branch-name or git push origin branch-name:master or git push origin branch-name:another_branch</code></li>
    <small>Here, branch-name is the same as HEAD and they both are interchangable</small>

  </ul>
  <li><h2>Clone A Repository</h2></li>
  <li><h2>SET UP GIT MANUALLY</h2></li>

</ol>
</div>
</body>
</html>