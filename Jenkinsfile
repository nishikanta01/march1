pipeline{
   agent {
  label 'first'
}

     stages
         {
         stage("GIT")
             {
             steps
                 {
                 git "https://github.com/nishikanta01/march1.git"
                 }
             }
         stage("run")
             {
             steps
                 {
                 sh "java Demo.java"
                 }
             }
         }
       }
