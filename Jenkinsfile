pipeline{
   agent any
   stages{
      stage("Start building app") {
         steps{
            echo "Start Building app echo"
         }
      }
      stage("Start testing app") {
	 when{
	    expression{
		BRANCH_NAME=='dev'
	    }
         }
         steps{
            echo "Start testing app"
         }
      }
   }
}
