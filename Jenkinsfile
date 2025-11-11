pipeline 
	{
	agent any
		stages 
			{
			stage ('one')
				{
				steps 
					{
						echo "this is stage 1"
	      		}
      		}
			
			stage ('cp')
				{
				steps 
					{
						echo "This is Stage of Copying Index File"
						sh "cp -r /root/.jenkins/workspace/httpd-pipeline/index.html /var/www/html/index.html"
	      		}
      		}
    	}
}
