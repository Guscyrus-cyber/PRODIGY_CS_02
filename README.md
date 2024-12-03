# encrypted_decrypted_image
In this project, I started by converting an unencrypted image on my kali Linux desktop into a bytearray using a Python script. The bytearray allows me to work with the raw binary data of the image, which is necessary for encryption and decryption. By reading the image file in binary mode, I was able to load its contents into a bytearray and prepare it for the next step in the process.

Next, I used the Python script to apply a simple XOR encryption to the image's bytearray. This encryption method involves performing an XOR operation on each byte of the image with a specified key, making the image unreadable in its encrypted form. Then I wrote the encrypted data back into a new image file. To restore the original image, I applied the same XOR operation with the same key to decrypt the file, effectively reversing the encryption and recovering the image to its original state.
## License
This project is licensed under the MIT License

## Sponsership
This project is sponsered by Prodigy InfoTech
