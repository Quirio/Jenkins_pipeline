def project_repository = 'https://github.com/Quirio/Jenkins_pipeline.git' 
node {
    stage('Build') { // <2>
      git 'https://github.com/Quirio/CookAdventure_TFM_UNIR.git'
    }
    stage('Test') {
       echo 'Hello test'
    }
    stage('Deploy') {
       echo 'Hello deploy'
    }
}
