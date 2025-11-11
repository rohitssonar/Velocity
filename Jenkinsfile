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
         				echo "Changing dir & Copying"
						sh "cp -r /index.html /var/www/html/index.html"
	      			}
      			}
    	}
}
