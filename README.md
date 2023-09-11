# StableThumbs
<img src="https://img.shields.io/badge/diffusers-yellow" /> <img src="https://img.shields.io/badge/Text2Img-blue" /><br>
This repo contains the training script for StableDiffusion + Dreambooth for Thumbs-up style photo generation. We fine-tune a StableDiffusion v1.5 model to allow 'a thumbs up' gesture. We also train the model to learn the face of professional soccer player Vinicius Jr., and incorporate the thumbs-up style with images of him.

The model can be found at [https://huggingface.co/sanjeevnara/stablethumbs-dreambooth-multiconcept](https://huggingface.co/sanjeevnara/stablethumbs-dreambooth-multiconcept)

Example Images:
<table border="0" cellspacing="20">
      <tr>
          <td>
              <h2>Generated Images</h2>
              <img src="https://github.com/sanjeevnara7/StableThumbs/blob/main/samples/Vinijr_sample1.jpeg" style="width: 110px; height: 110px;">
              <img src="https://github.com/sanjeevnara7/StableThumbs/blob/main/samples/Vinijr_sample2.jpeg" style="width: 110px; height: 110px;">
              <img src="https://github.com/sanjeevnara7/StableThumbs/blob/main/samples/Vinijr_sample3.jpeg" style="width: 110px; height: 110px;">
          </td>
          <td>
              <h2>Real Images</h2>
              <img src="https://img.asmedia.epimg.net/resizer/FWw5DSsYxQz-VVa8KaqtfSu8zIw=/1472x1104/filters:focal(2724x1576:2734x1586)/cloudfront-eu-central-1.images.arcpublishing.com/diarioas/QN27ZCZYKBEI7J2HAZLR4GSYXU.jpg" style="width: 110px; height: 110px;">
              <img src="https://images2.minutemediacdn.com/image/fetch/https%3A%2F%2Ftherealchamps.com%2Fwp-content%2Fuploads%2Fgetty-images%2F2018%2F08%2F1247365071.jpeg" style="width: 110px; height: 110px;">
              <img src="https://imgresizer.eurosport.com/unsafe/2560x1440/filters:format(jpeg)/origin-imgresizer.eurosport.com/2022/07/06/3404997-69580108-2560-1440.jpg" style="width: 110px; height: 110px;">
          </td>
      </tr>
  </table>
