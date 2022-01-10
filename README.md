# Escaping-Criminal-Car-Tracking-System-Using-Number-Plate-Detection-and-Image-to-Text-Approch
This Project is completed by Jayvardhan and Khushvardhan Bhardwaj.
A reference/help for the same was taken from the Github account of Shaily priya and also from Geeks For Geeks website.
This Project will scan the number plates from the Surveillance camera and save them in a jpg format, followed by scanning and extracting the text in those images into a text file.
- The code starts by importing the necessary libraries.
- It then imports the pickle library, which is used to save and load data from a file.
- The next line of code creates an Image object using PIL, which is used for loading images into Python.

- The main function starts with a list comprehension that reads in all of the text files found in the current directory (the one where this script resides).
- This list comprehension uses os.path.abspath() to get the path of each file and store it in a variable called files_in_dir .
- Then it loops through these files and calls pytesseract on each one, passing them as arguments to tesseract .
- Finally, it prints out "Successfully processed" if everything went well or else prints out an error message if something went wrong with any of the processes.- The code will open up a window with the text "Tesseract" in it.

- The code will then use the Tesseract library to read any text that is inputted into the window and convert it into an image.

- The code will then store this image file in a folder on your PC called "C:\Program Files (x86)\Tesseract-OCR\".- The code starts by importing the necessary libraries.
- It then creates a variable called "cap" which is used to capture video from the webcam.
- The code sets the width and height of the captured image to 640x480 pixels, respectively.
- Next, it loads up a model for detecting number plates with cv2.CascadeClassifier("number_plate_scanning_model.xml").
- Then it defines variables that will be used later in this program: minArea = 500, color = (255,0,255), cap = cv2.VideoCapture(0).

- The main loop starts off by setting count to 0 and waiting until there is an image available on the camera's frame buffer before continuing on with its execution logic.
- Once an image has been read successfully from the camera's frame buffer, grayimage is created using cv2.cvtColor().
- This function converts any pixel value between 0-255 into grayscale values between 0-1 where black represents zero and white represents one; this allows us to see what parts of our images are pure black or pure white without having to worry about colors getting lost in translation when we convert them back into RGB values later on in our program!
- After creating grayimage we call- The code is a function that will loop through the number of plates in an image and then detect them.

- The code starts by importing the necessary libraries for the program to run.

- Next, it creates a function called "main" which will be used as the entry point for all other functions.

- The first line of main sets up some variables for use throughout the rest of the program.
- The variables are: fwidth, fheight, nPlateCascade, minArea, color and cap.

- Next, we have a while loop that will keep running until there is no more data to read from the video capture device (cap).
- The while loop contains two parts: success and img = cap.read().
- Inside- The code starts by importing the necessary libraries.
- Next, it creates a new image with the dimensions of 500x500 pixels.
- It then sets up an empty list called images and initializes it to be empty.
- The code then loops through all of the numbers from 1-999 in order to create a number plate for each one.
- For each number plate, it creates a rectangle that is 500x500 pixels and fills it with black color using cv2.rectangle().
- It then puts text on top of the image saying "Number Plate" at (x=0, y=5).
- After creating all nine plates, it displays them as an array using cv2.imshow("Scan",newimg) function before saving them as jpg files in scanned_images folder under current working directory where they are named according to their respective count value which starts from 1 and ends at 9

- The code begins by importing required libraries such as OpenCV 2 library and NumPy package which will help us perform mathematical operations like calculating area or finding out if there is enough space for our desired shape on the given image

- Next we initialize variables w*h which stands for width * height respectively

- If w*h>minArea: this means- The code is used to scan a number plate and then create an image of the scanned result.

- The code above takes in the width and height of the image, calculates the area of that particular image and then creates a rectangle with those dimensions on top of it.

- The code above then puts text over the rectangle with a font size of 1, color being red and opacity being 2.- The code starts by creating a string called text.
- This is the output of the program, which will be displayed in a loop.
- The code then creates an empty list called d and sets it to "".

- d=str(text[:-1])

- The code uses str() to create a new string with just one character from the original string.
- It does this for every element in text until it reaches the end of text, at which point it returns "".- The code is meant to read the contents of a .jpg file and convert it into text.

- The code starts by creating an instance of Image1, which is the name of the variable that will hold the image file's content.
- The code then uses pytesseract.tesseract_cmd=path_to_tesseract to point tesseract at the image file that was just created.
- Lastly, it prints out all but one character from the string that was returned by tesseract.
