<p align="center">
  <a href="https://www.perceptilabs.com">
  <img src="./pl_logo.png">
  </a>
</p>

# Ways-to-Wear-a-Face-Mask

This dataset<sup>1</sup> contains images of people wearing face masks.

The data can be used to build and train an ML model that can detect the presence and correct positioning of face masks (e.g., for protecting against COVID-19).

# Structure

This repo contains the following structure:

- **mask_log.csv**: CSV file for use in loading the data into PerceptiLabs.

Due to the large number of images, the dataset must be downloaded from [https://ieee-dataport.org/open-access/ways-wear-mask-or-respirator-wwmr-db](https://ieee-dataport.org/open-access/ways-wear-mask-or-respirator-wwmr-db).

The following shows an example of images from the dataset:

<p align="center">
  <img src="./mask_sample.png">
</p>

The following shows a partial example of the data stored in **mask_log.csv** that is used to load the data into PerceptiLabs: 

| **image_path** | **target** |
|------------|--------------|
| Mask_Above_Chin/0001_MSFC_NMDM_0000.jpg | 0 |
| Mask_Correctly_worn/0001_MRCW_DRNV_0000.jpg | 1 |
| Mask_Hanging_From_Ear/0001_MRHN_DRNV_0000.jpg | 2 |
| Mask_Not_Worn/0001_MRNW_0000.jpg | 3 |
| Mask_On_Forehead/0001_MRFH_DRNV_0000.jpg | 4 |
| Mask_On_Tip_Of_Nose/0001_MRTN_DRNV_0000.jpg | 5 |
| Mask_Under_Chin/0001_MRNC_DRNV_0000.jpg | 6 |
| Mask__Under_Nose/0001_MRNN_DRNV_0 | 7 |

The values in the **target** column indicate the respective mask-wearing state depicted in each image:

0 - mask above chin<br/>
1 - mask worn correctly<br/>
2 - mask hanging from wearer's ear<br/>
3 - mask not worn<br/>
4 - mask on forehead<br/>
5 - mask on tip of nose<br/>
6 - mask under chin<br/>
7 - mask under nose

# Community

Got questions, feedback, or want to join a community of machine learning practitioners working with exciting tools and projects? Check out our [Community](https://forum.perceptilabs.com/)!

<sup>1</sup> Dataset Credits: https://ieee-dataport.org/open-access/ways-wear-mask-or-respirator-wwmr-db
