# Matlab-Image-Processing-Old-Project
Its an old project i worked on during 2020 for a course in engineering, It was on Matlab also i was endorsed by the faculty on it for which i was issued an official letter.I am posting this repo as just a "collection" of my works.

# This Project was processed on Matlab [https://www.mathworks.com/]

![Internship-on-Image-Processing-using-MATLAB-IETE-1](https://user-images.githubusercontent.com/34340232/177779465-fd303cb2-9165-4804-90e7-ffe04342d597.jpg)



# Figure 1

![image](https://user-images.githubusercontent.com/34340232/177776089-51801c93-0fb1-42e8-a33b-c5c58f002b46.png)

```
clear all
clc
A='/ MATLAB Drive Figl.tif';
B=imread(A,'tif'); 
C=rgb2gray(B);

figure(1), imshow(B), title( 'Original Image');
figure(2), imshow(C), title('Gray Image');

subplot(1,2,1), imshow(B), title('Original Image'); 
subplot(1,2,2), imshow(C), title('Gray Image');

imrite(C,'/MATLAB Drive/Fig1_gray.jpe');
```

# Figure 2

![image](https://user-images.githubusercontent.com/34340232/177777377-0af426c8-7dd1-4327-ba38-a7155deaf434.png)

```
clear all 
clc 
A='/ MATLAB Drive/Fig2.tif';
B=imread(A,'tif');
C=rgb2gray(B);

figure(1), imshow(B), title( 'Original Image');
figure(2), imshow (C), title('Gray Image');

subplot(1,2,1), imshow(B), title('Original Image');
subplot(1,2,2) , imshow(C), title('Gray Image');

imurite(C, '/MATLAB Drive/Fig2_gray.jpg');
```
# Figure 3

![image](https://user-images.githubusercontent.com/34340232/177778292-519d916f-b3d1-4c1f-99d6-a15702779f06.png)

```
clear all 
clc 
A='/ MATLAB Drive/Fig3.tif';
B-imread(A, 'tif'); 
C=rgb2gray(B);

figure(1), imshow(B), title('Original Image');
figure(2), imshow(C), title('Gray Image');

subplot(1,2,1) , imshow(B), title('Original Image');
subplot(1,2,2) , imshow(C), title('Gray Image');

imwrite(C, '/MATLAB Drive/Fig3_gray.jpg');
```
# Figure 4

![image](https://user-images.githubusercontent.com/34340232/177778547-09ca0402-31c8-4cf2-9f35-a88d453816b7.png)

```
clear all 
clc 
A='/ MATLAB Drive/Fig4.tif';
B-imread(A, 'tif'); 
C=rgb2gray(B);

figure(1), imshow(B), title('Original Image');
figure(2), imshow(C), title('Gray Image');

subplot(1,2,1) , imshow(B), title('Original Image');
subplot(1,2,2) , imshow(C), title('Gray Image');

imwrite(C, '/MATLAB Drive/Fig4_gray.jpg');
```



