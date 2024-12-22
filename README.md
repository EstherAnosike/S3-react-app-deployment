<h1> S3 Bucket-React-app-Deployment </h1>

Step 1: Create an S3 Bucket

- Click the Create Bucket button.

- Configure the bucket settings:

- Bucket Name: Provide a unique name (e.g., "demo-food-app-bucket").

- Region: Choose the AWS region closest to your users.

- Bucket Settings for Block Public Access:

- By default, block all public access. If you plan to make the bucket public, adjust these settings accordingly.

- Bucket Versioning (Optional): Enable versioning if you want to maintain multiple versions of objects in your bucket.

- Encryption (Optional): Enable default encryption for data at rest.

- Click Create Bucket.

Step 2: Upload Objects to the Bucket

- Open the newly created bucket from the S3 Dashboard.

- Click Upload.

- Drag and drop the BUILD files or click Add Files to select them from your computer.

- Finally Click Upload to store the files in the bucket.

Step 3: Manage Bucket Permissions

- Navigate to the Permissions tab of the bucket.

- Configure access policies based on your needs:

- Bucket Policy: Use a JSON policy to define access permissions.

- Access Control List (ACL): Set permissions for specific AWS accounts or the public.

*For public buckets, ensure that the "Block Public Access" settings are adjusted and the bucket policy allows public access.*

Step 4: Access Objects in the Bucket

- Go to the Objects tab of your bucket.

- Click on any object to view details.

- Use the Object URL to access the file (if public access is enabled).

Step 5: Enable Static Website Hosting

- Go to the Properties tab of the bucket.

- Scroll down to Static Website Hosting and click Edit.

- Enable static website hosting and provide the following:

Index Document: Specify the main page (e.g., index.html).

Error Document: Specify the error page (e.g., error.html).

Save changes.


Now you can use the Endpoint URL provided to access your static website!