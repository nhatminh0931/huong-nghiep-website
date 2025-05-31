# Make sure you're in your project directory
cd huong-nghiep-website

# Initialize git repository
git init

# Add your GitHub repository as the remote origin
git remote add origin https://github.com/nhatminh0931/huong-nghiep-website.git

# Create a .gitignore file (if not already present)
echo "node_modules/
.next/
.env.local
.env
dist/
.DS_Store" > .gitignore
