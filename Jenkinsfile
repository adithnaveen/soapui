
node {
        stage('Checkout') {
            git url: 'https://github.com/adithnaveen/soapui.git',  branch: 'master'
            echo '****************CHECKOUT SUCCESSFUL****************'
        }
       

       stage('Run Tests') {
	bat 'C:/Program Files/SmartBear/SoapUI-5.5.0/bin/testrunner.bat -r -j REST-Project-1-soapui-project.xml'
			echo '****************DOCKER DEPLOY SUCCESSFUL****************'
        }

}
