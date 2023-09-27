# YAML for ci-cd

# Key concepts for AzureDevops Pipeline

  ..Hierarchy<br>
         ->Stage<br>
           ->job:Each job runs on an agent<br>
             ->step:script/task<br>

# Pipeline Design methods

   ->Classic ViewUi<br>
   ->YAML view scripting<br>


# Pipeline using ClassicViewUI

  ->Click Pipelines<br>
  ->Click Newpipeline<br>
  ->Click Use the classic editor<br>
  ->Select repository<br>
  ->Click Empty job<br>
  ->Click Queue<br>
  ->Run<br>

# Pipeline using YAML view scripting

  ->Click Pipelines<br>
  ->Click Newpipeline<br>
  ->Click Azure repos Git<br>
  ->Select repo<br>
  ->Configure--Starter pipeline<br>
  ->Save and run<br>

# YAML Pipeline Schema


 Define Trigger to manual or automatic<br>
 ->trigger:<br>
   - master<br>
 <br>
 Agents info MS/local<br>
 ->pool:<br>
    //vmImage: ubuntu-latest<br>
 <br>
 stages:  ...array<br>
  - stage:A  ...item<br>
    jobs:    ...array<br>
     - jobs:A ...item<br>
       steps:   ...array<br>
        - script:echo "A"  ...item<br>
  <br>

  
  

 








     


