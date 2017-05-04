
node 'base'{
  
  try {
	stage 'Checkout'
		checkout scm

	stage 'Build'
		sh 'echo "building..."'
  
	stage 'Archive to artifactory'
		sh 'echo "upload to artifactory"'
  }

}
