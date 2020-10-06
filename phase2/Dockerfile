# Project: Run an express app in a Docker container

# Step 1: Use the 'node' official image, version 6.x, for alpine 6.x

# Step 2: Look in the app.js to determine which port to expose

# Step 3: Use alpine package manager to install tini: 'apk add --update tini'
# Step 4: Create a new directory for app files using 'mkdir -p /usr/src/app'
#   Chain commmands together to reduce the number of layers in the image

# Step 5: Ensure the rest of the instructions are working in the new folder

# Load and install packages before applications files for better caching

# Step 6: Since node uses a "package manager", copy in 'package.json' and the
# corresponding lock file

# Step 7: Install dependencies using npm
#   To keep the image clean and small, run 'npm cache clean --force' after

# Step 8: Copy in all files from current directory

# Step 9. Run the application with command '/sbin/tini -- node app.js'.
#   Lookup the CMD syntax if you need a reminder.