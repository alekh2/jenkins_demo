echo 'hello world!!';

node{
    stage('Fetch'){
        checkout scm;
        python seventh.py;
    }
    stage('Test') {
        echo 'Testing';
        assert false;
    }
 
    stage('Build') { // <2>
        echo 'building';// <3>
    }
    
    stage('kabutar'){
        echo 'gutur gu!! gutur gu!!'
    }
    
}
