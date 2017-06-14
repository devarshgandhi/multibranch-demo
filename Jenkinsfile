node {
   // Mark the code checkout 'stage'....
   stage 'Checkout'

   // Checkout code from repository
   checkout scm
   
   // Mark the code build 'stage'....
   stage 'Build'
   // Print Statement
   echo "This is Test Build"
   
   stage 'Downstream Job'
   build job: 'multibranch_demo'
}
