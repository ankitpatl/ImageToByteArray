# ImageToByteArray

if you want to convert image to byte array

string path = HttpContext.Current.Server.MapPath("~/image/noimage.jpg");
photo = File.ReadAllBytes(path);
