
@Library('potatocannon-global')
import au.com.tabcorp.potatocannon.*
import groovy.json.JsonOutput

node 'base'{
  
  try {
	stage 'Checkout'
		checkout scm

	stage 'Build'
		sh 'echo "building..."'
  
	stage 'Archive to artifactory'
		sh 'echo "upload to artifactory"'
  } catch (e) {
        sh 'echo "build failed..."'
        }
      throw e
      

}
