To run this application on your machine follow these steps:
1. git clone  https://github.com/Harshktk/Computer_hub_assi.git

2. Open the code in code editor

3.Open terminal

4.Enter command - npm i

5.To start application - npm run dev



To run this application on your machine follow these steps:

1. git clone  https://github.com/Harshktk/Computer_hub_assi.git

2. Open the code in code editor

3.Open terminal

4.Enter command - npm i

5.Create a .env file

6. Add the below code in .env file

###########################################################################
# Required from externals tools.
OPENAI_API_KEY="sk-None-GQu4nv4a3Q7vLVzPRi80T3BlbkFJIv5492sLVqHJKE8LrKK3"
PINECONE_API_KEY="ac38164c-164a-4c05-b135-08b053cda4e2"

# Usually for free pinecone account env is "us-west4-gcp-free"
PINECONE_ENVIRONMENT="gcp-starter"

# The index can be created directly or will
# be created when you run prepare-data npm command
PINECONE_INDEX_NAME="chatboot"

# A user defined name space is better to help pinecone where to look
PINECONE_NAME_SPACE="name_b"

# Path to your file
PDF_PATH="./docs/Corpus.pdf"

# Pinecone index creation requires time so hence we wait for 3 minutes
# If you dont want to wait, create index on the pinecone console 
# https://app.pinecone.io/organizations
INDEX_INIT_TIMEOUT=240000


######################################################################

7.npm run prepare:data

8.npm run dev

9.In your browser open - http://localhost:3000/



Tech used:

1.Next.js

2.Typescript

3.Openai as chatgpt

4.Langchain

5.Pinecone index as vector database



