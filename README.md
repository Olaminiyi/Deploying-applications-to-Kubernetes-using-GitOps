# Deploying-applications-to-Kubernetes-using-GitOps
 configjob:
    runs-on: ubuntu-latest 

       steps: 
       - name :
         id: Configure AWS Credentials
         uses: aws-actions/configure-aws-credentials@v1
         with:
            aws-access-key-id: ${{ secrets.AWS_ACCESS_KEY_ID }}
            aws-secret-access-key: ${{ secrets.AWS_SECRET_ACCESS_KEY }}
            aws-region: us-east-1