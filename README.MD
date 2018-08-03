<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8" />
<meta http-equiv="X-UA-Compatible" content="IE=edge">
</head>
<body style="background-color: #123123;">
<div>

  
<h1>STEPS TO GIT ON THE COMMAND LINE</h1>
 <b>Whether you want to contribute to an existing project or you want to set up a new one, these basic steps will get you covered.</b>
<ol>
  <li><h2>Clone A Branch</h2></li>
  <ul>
    <li><code>git clone -b branch-name https://github.com/user/repo.git #This creates a new repo for you offline</code></li>
    <li><code>cd repo #Meaning change into the newly created repo</code></li>
    <li><code>git rm -rf . #If you'd lie to clean up and start afresh, that's the code</code></li>
    <li>git checkout --orphan you-new-branch-name or git checkout -b new-branch-name #meaning create new branch</li>
    <b>Then create files and add them there</b>
    <li><code>git add -A #Git stage all files and folders in this directory</code></li>
    <li><code>git commit -a -m "Real good message about the upload"</code></li>
    <li><code>git push origin branch-name:branch-name or git push origin branch-name:master or git push origin branch-name:another_branch</code></li>
    <b>Here, branch-name is the same as HEAD and they both are interchangable</b>

  </ul>
  <li><h2>Clone A Repository</h2></li>
  <li><h2>SET UP GIT MANUALLY</h2></li>

</ol>
</div>
</body>
</html>