# Amazon_apparel_recommendation_workshop
In this workshop there are techniques used like Bag of words, TF-IDF, word2vec.

due to size limit i am not able to add all the files here.

## Overview
**Step wise explanation:**

1. Import all the libraries

2. import data

3. Explore the dataset/features like Color,Brand,Asin(Amazon Standard Identification Number),Medium_img_url,Product_type_name title and formated price.

4. Considering Price and color features where we have not null(all) the values. we have nearly 28k data where all the rows 
filled with "price" and "color".
   
   **now file size reduced to "183k ---> 28K"**

5. Remove duplicates

6. Sort these 27949 products by Alphabetical order.

7. After sorting few titles differ only by the last words.

8. Hence,they are alphabetically sorted , consider first two and split them to words.

9. after that data reduced to 17593.
   
   **now file size reduced to "28k to 17k"**

10. Even after removing adjacent titles, there are some more duplicates. after deleting them.

     **now file size reduced to "17k to 16k"**

11. Applied stopwords on this 16k data. save file as "16K_apparel_preprocessed_data".

12. Applied Bag of words.

13. Applied TF-IDF.

14. Applied IDF.

15. Applied Word_2_vec just to compare the performance to 12,13,14 points.

16. Average word_2_vec

17. IDF weighted word_2_vec model

18. Till now we did simularity using Title, now do the same to Brand, Color.

19. Deep learning visual model recommendation usinig tensorflow and keras.

2. A/B testing.
