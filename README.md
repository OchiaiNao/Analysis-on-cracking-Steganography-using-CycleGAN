# Analysis on cracking MSB and DWT using CycleGAN

datasets:
## datasets are categorized by image shapes

- total      # 4319 elements

- most # 469  elements with the highest count

- second # 368  elements with second-highest count

- third # 294  elements with third-highest count

We randomly get 422 images from most, the rest are for valid. 
Get all 294 images from the third folder, and resize them to the shape of (1024, 768, 3). 

Files in ./train/cover/class1: 211-15 from ./most, 147 from ./third, total 343 

Files in ./train/hidden/class1: 211-15 from ./most, 147 from ./third, total 343

Files in ./train/stego/class1: generated from cover and hidden 1 to 1 and 1 to many (343 * 15 = 5145)

Files in ./valid/cover/class1: 23 from the rest of the most

Files in ./valid/hidden/class1: 23 from the rest of the most

Files in ./valid/stego/class1: generated from cover and hidden 1 to 1 and 1 to many (343 * 15 = 5145)

Files in ./test/cover/class1: 15 from train folder

Files in ./test/hidden/class1: 15 from train folder

Files in ./test/stego/class1: generated from cover and hidden 1 to 1 and 1 to many (343 * 15 = 5145)

