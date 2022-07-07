# Matlab-Image-Processing-Old-Project
Its an old project i worked on during 2020 for a course in engineering, It was on Matlab also i was endorsed by the faculty on it for which i was issued an official letter.I am posting this repo as just a "collection" of my works


![image](https://user-images.githubusercontent.com/34340232/177776089-51801c93-0fb1-42e8-a33b-c5c58f002b46.png)

''' clear all
clc
A='/ MATLAB Drive Figl.tif';
B=imread(A,'tif'); 
C=rgb2gray(B);

figure(1), imshow(B), title( 'Original Image');
figure(2), imshow(C), title('Gray Image');

subplot(1,2,1), imshow(B), title('Original Image'); 
subplot(1,2,2), imshow(C), title('Gray Image');

imrite(C,{MATLAB Drive/Figi_gray.jpe'); '''
