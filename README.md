# GAN-with-pytorch

![Screenshot (6)](https://user-images.githubusercontent.com/65830412/157689433-14ea9836-34a9-45f0-9760-63769ba57503.png)


# And the schematic of me the GAN model looks like:

![0__PEWcPKaXEBla9pP](https://user-images.githubusercontent.com/65830412/157690269-f261421b-c0c6-4cbc-84e0-37e26f18183b.png)

Generator must be more powerful network than the Discriminator, because it generates images, while the second one is just a binary classification (map 0/1).

At the end of the code we can see that as long as we pass through the epochs the generator represents better and better the MNIST dataset, making the Discriminator's task to detect whether an image is real or fake very difficult(even to our eyes).
