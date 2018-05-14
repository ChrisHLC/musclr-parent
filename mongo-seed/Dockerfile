# Create image based on the official Node 6 image from the dockerhub
FROM mongo:3

# Copy dump folder
COPY dump /dump

# restore the data from the dump
CMD mongorestore --host mongodb dump