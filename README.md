# serverless-app-examples
Getting started with AWS Serverless Application
<br><br>
[hand on Learning](https://aws.amazon.com/getting-started/hands-on/run-serverless-code/)

## hello world 

```

import json

def lambda_handler(event, context):
    # TODO implement
    return {
        'statusCode': 200,
        'body': json.dumps('Hello from Lambda!')
    }


```

![image](https://user-images.githubusercontent.com/67835881/150406929-b170206e-1799-4693-afd2-1e709b030950.png)
