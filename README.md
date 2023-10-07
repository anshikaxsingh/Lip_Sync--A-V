# Lip_Sync--A-V
AI model that is proficient in lip-syncing i.e. synchronizing an audio file with a video file.

## Cloning of git repo

https://github.com/zabique/Wav2Lip

## Downloading a Model Checkpoint:

   - Use the following command to download a pre-trained model checkpoint:
   - 
     !wget 'https://iiitaphyd-my.sharepoint.com/personal/radrabha_m_research_iiit_ac_in/_layouts/15/download.aspx?share=EdjI7bZlgApMqsVoEUUXpLsBxqXbn5z8VTmoxp55YNDcIA'


     Saving the .pth file
     
     ``-O '/content/Wav2Lip/checkpoints/openinapp.pth'``
     
   - This command saves the downloaded checkpoint as `openinapp.pth` in the `/content/Wav2Lip/checkpoints/` directory.



## Installing the `ghc` Python Package:

   - Install the `ghc` Python package using the following command:
     python --
     ``a = !pip install https://raw.githubusercontent.com/AwaleSajil/ghc/master/ghc-1.0-py3-none-any.whl``
     (for reference)

## Install Required packages/libraries as mentioned in the requirement.txt:

     librosa==0.7.0
     numpy==1.17.1
     opencv-contrib-python>=4.2.0.34
     opencv-python==4.1.0.25
     torch==1.1.0
     torchvision==0.3.0
     tqdm==4.45.0
     numba==0.48
     

## Lip-syncing videos using the pre-trained models (Inference):

    !cd Wav2Lip && python inference.py --checkpoint_path checkpoints/(your generated .pth file) --face "path of video" --audio "audio path".



Download the generated video

In the pasted drive link you will find .pth file for both Wav2lip(GAN) and Face Detection:

https://drive.google.com/drive/folders/1q5uDGIJuVgd5tcS4CJuQie8GGQsDPmm-?usp=sharing




     
