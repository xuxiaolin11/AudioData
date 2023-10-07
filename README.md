# AudioData

## Regarding the "Figure 7" folder and the "Figure 8" folder.

   **figureX_X_denoised.wav**:Representing files that have undergone model-based denoising and enhancement processing.For example, "figure7_e_denoised.wav" represents the audio file corresponding to Figure 7, the "e" spectrogram, and it is the audio file after denoising.<br>
                            
   **figureX_X_RecordX.wav**:It represents the audio file of channel X from Figure X without denoising. For example, "figure7_a_Record.wav" represents the audio file corresponding to Figure 7, the "a" spectrogram, and it is the mixed audio file without model processing.<br>All the audio files are synthesized by adding noise to clean drilling vibration signals.  <br>
   **background_noise.wav**:These represent noise files added during the synthesis of the dataset. These noise files were recorded under field conditions.<br>
## Regarding the "Train-data" folder<br>
The data in the "Train-data" folder and the data in the "Figure 7" and "Figure 8" folders have the same source. <br>
This is a folder containing a training dataset of 20 examples, using two   vibration sensors as an example.<br>
  **background_noise.wav**:These represent noise files added during the synthesis of the dataset. These noise files were recorded under field conditions.<br>
  **RecordX-clean.wav**:   X represents the vibration sensor number, and it represents the clean drilling vibration signal.The clean drilling vibration signals were collected in a quiet lab using data acquisition boards. For this portion, we performed preprocessing operations to remove segments that did not contain drilling vibration signals.<br>
  **RecordX-mix.wav**:     X represents the vibration sensor number, and it represents the mixed drilling vibration signal with added noise, which is used for model inference and training. <br>                         	
## Regarding the "Figure 9" folder and the "Figure 10" folder.

   **figureX_X_denoised.wav**:Representing files that have undergone model-based denoising and enhancement processing.For example, "figure9_e_denoised.wav" represents the audio file corresponding to Figure 9, the "e" spectrogram, and it is the audio file after denoising.<br>
                            
   **figureX_X_RecordX.wav**:It represents the audio file of channel X from Figure X without denoising. For example, "figure9_a_Record.wav" represents the audio file corresponding to Figure 9, the "a" spectrogram, and it is the mixed audio file without model processing.<br>	All the audio files are recorded from real outdoor environmental data without any additional processing. We extracted audio files containing valid drilling vibration signals from over 50 hours of recorded audio, processed them into 3-second segments, and input them into the model for processing.<br>			            
   

    
