# Coin Text dataset
We released an irregular coin text dataset for end-to-end text recognition tasks.

# what it contains?
It contains 1382 train images, 303 test images and manually annotated labels in the form of .json.

The images are collected from  www.worldcoindatabase.com, https://onlinecoin.club/Coins/List/ and https://www.coin-database.com/series/.

Text in this dataset is either regular or arc text. 

Some Examples:

![0000332](https://user-images.githubusercontent.com/44936161/160741443-8e4dab8f-fa35-4c7b-a615-bac0b0dd6aa0.jpg)
![0000017](https://user-images.githubusercontent.com/44936161/160740182-5c305579-05b5-49e1-a99a-4834abf670ca.jpg)
![0000033](https://user-images.githubusercontent.com/44936161/160740194-6a63ca27-2c1f-4594-845b-77831a092c24.jpg)
![0000047](https://user-images.githubusercontent.com/44936161/160740200-972113ee-a20d-406d-94c7-076f41f283ea.jpg)

# what are the form of the annotation?
For a text instance, it is labelled with 6 points. 3 points to represent the top arc boundary and another 3 to represent the bottom boundary.

The first 3 points are start, near middle and end points of the top boundary, its direction is the same as reading direction.

The last 3 points are listed against the reading direction.

Examples are like this:

![1](https://user-images.githubusercontent.com/44936161/160740795-5e7e0da0-5731-4e62-8e0b-7638724e1116.png)
