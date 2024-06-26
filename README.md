# ImageSearchVideo

An image search corresponds to a video application

After extracting videos into multiple images by frame, the extracted features of the images are converted into embeddings

Searching for Similar Images through Vector Search

# 1.install

   ## docker
   
      $ git clone https://github.com/RebeccaDeng-133/ImageSearchVideo.git
      
      docker-compose up -d
      
   ## IPM

      zpm install imagesearchvideo


      python3 -m pip install --target /usr/ImageSearchVideoPython opencv-python 

      python3 -m pip install --target /usr/ImageSearchVideoPython scikit-image 

      python3 -m pip install --target /usr/ImageSearchVideoPython nltk 
      
      
# 2.Usage

     1.Visit the localhost:52773/csp/user/ImgSearchVideoIndex.csp

     2.点击uploadvideo
     
      Upload video (note: it takes some time, you can check if it is completed on the message tracking page, the test video was recorded by myself)

  ![image](https://github.com/MJQ-jh/ImageSearchVideo/assets/71477062/bd7c6148-516d-4f59-b0e0-a290467610b7)

  ![image](https://github.com/MJQ-jh/ImageSearchVideo/assets/71477062/c09fe6e2-45c7-4695-8b0a-984a3ed8b0cc)


     3.Click search

  ![image](https://github.com/MJQ-jh/ImageSearchVideo/assets/71477062/98dd33b5-c455-48e7-91ba-de19622cd2cd)

       Upload images
       
     4.The query result appears on the right side
     
      Display video name/approximate time/similarity
       
![b4eb243d20c8b8237ea191c027a7976](https://github.com/MJQ-jh/ImageSearchVideo/assets/71477062/7cc7d457-cf19-4d91-8c49-1df4d03631ae)


