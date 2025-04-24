pipeline{
    agent any
    stages(){
        stage("stage1"){
           steps{
            echo 'Welcome to first Declerative Pipeline';
            sh 'whoami';
            sh'apt update && apt upgrade -y';
            sh'apt install sudo -y';
            sh'sudo apt install docker.io -y && apt install docker-compose -y';
            sh'docker --version';
            sh'docker-compose version';
            sh'docker image build -t radhika913/24april2025:v1';
             sh'docker image ls';
}

}


}
}
        }
    }
