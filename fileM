import os 
import shutil

filename = os.listdir("./")
if ("imgFile" not in filename):
	os.mkdir("imgFile")

for file in filename:
	print(file)
	if ("." in file):
		filespl = file.split(".")
		if (str(filespl[-1]) == "png"):
			shutil.move("./{}".format(file),"./imgFile/{}".format(file))
		elif(str(filespl[-1]) == "jpg"):
			shutil.move("./{}".format(file),"./imgFile/{}".format(file))
		elif(str(filespl[-1]) == "gif"):
			shutil.move("./{}".format(file),"./imgFile/{}".format(file))
		elif(str(filespl[-1]) == "jpeg"):
			shutil.move("./{}".format(file),"./imgFile/{}".format(file))
