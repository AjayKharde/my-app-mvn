  node{
   stage('SCM Checkout'){
     git 'https://github.com/javahometech/my-app'
   }
    
    stage('Email Notification'){
      mail bcc: '', body: '''Hi Welcome to jenkins email alerts
      Thanks
      Hari''', cc: '', from: '', replyTo: '', subject: 'Jenkins Job', to: 'ajay.kharde@gmail.com'
   }
    
  }


