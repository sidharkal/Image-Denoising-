# Denoising Dirty Documents

This is the kaggle problem you can found Dataset Here (https://www.kaggle.com/c/denoising-dirty-documents/data)

##  Problem
in this problem Optical Character Recognition (OCR) is the process of getting type or handwritten documents into a digitized format. If you've read a classic novel on a digital reading device or had your doctor pull up old healthcare records via the hospital computer system, you've probably benefited from OCR.

OCR makes previously static content editable, searchable, and much easier to share. But, a lot of documents eager for digitization are being held back. Coffee stains, faded sun spots, dog-eared pages, and lot of wrinkles are keeping some printed documents offline and in the past. 

This competition challenges you to give these documents a machine learning makeover. Given a dataset of images of scanned text that has seen better days, you're challenged to remove the noise. Improving the ease of document enhancement will help us get that rare mathematics book on our e-reader before the next beach vacation.

they provided two sets of images, train and test. These images contain various styles of text, to which synthetic noise has been added to simulate real-world, messy artifacts. The training set includes the test without the noise (train_cleaned). You must create an algorithm to clean the images in the test set.

## Evaluation Matrix

Submissions are evaluated on the root mean squared error between the cleaned pixel intensities and the actual grayscale pixel intensities.
