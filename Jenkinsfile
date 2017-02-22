node{
        stage('Build')
        {
                echo 'Build'
                sh      '''
                           echo 'import unittest' > test.py
                           echo 'print("hola!")' > test.py
                           python3 test.py
                        '''

        }
        stage('Test')
        {
                echo 'Test'
        }
        stage('Deploy')
        {
                echo 'Deploy'
        }
}
