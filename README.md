# Host-Static-Website-by-configuring-CORS
This is simple demonstration of hosting static website by using objects present in another S3 bucket by configuring CORS

# Implementation
1. Create a bucket by unchecking **Block all public access** , enable static website, add bucket policy 
2. In index file add the static website URL of cors along with <file.html> and save it
3. Upload index & error html files to the main bucket
4. Create a bucket , enable static website and upload loadpage & error html files
5. Configure CORS in the bucket which has the file that other bucket is trying to fetch
6. Host static website and verify if both index & loadpage contents are displayed on the website
