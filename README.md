# my_first_recognition

!wget 'IMAGE LINK'  ==>  Image'leri indirmek icin kullaniyoruz.

face_recognition.load_image_file('[!wget 'IMAGE LINK YAPINCA Saving to : ' LINK 'i koyuyoruz.']')  

face_recognition.face_locations('image')  ==> Yüzün yerini belirliyor.

face_recognition.face_encodings()[0] ==> (128,) float np.array yapiyor.

face_recognition.compare_faces(['IMAGE1'],'IMAGE2') ==> 2 Image'i karsılastirip aynı kisi olup olmadigini gösterir.

(top, right, bottom, left) = face_locations[0]  ==> Yüzü cevreleyen kutucuk icin.
