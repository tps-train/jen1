node {
  stage 'Checkout'
  checkout scm

  stage 'Build'
  sh 'echo "About to build Java app"'
  sh 'javac HelloWorld.java'

  stage 'Test'
  sh 'echo "Checking applicaiton works"'
  sh 'java HelloWorld | grep Hello'
}
