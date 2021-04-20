### LJSpeech Test Audios
<br>
## Results
<p class="text">Below Table Shows MOS with 95% Confidence Interval.</p>
<p class="text">LJSpeech Audio (22,050 sr) was downsampled to 16,000 before PESQ computation.</p>
<p class="text">GT - Ground Truth Audio.</p>
<p class="text">GT (Mel + WaveGlow) - first convert the ground truth audio into mel-spectrograms, and then convert the mel-spectrograms back to audio using WaveGlow.</p>

<br>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Method</b></td>
      <td style="text-align: center"><b>MOS (Author)</b></td>
      <td style="text-align: center"><b>MOS_LQO (Narrowband)</b></td>
      <td style="text-align: center"><b>MOS_LQO (WideBand)</b></td>      
    </tr>
    <tr>
      <td style="text-align: center"><i>GT</i></td>
      <td style="text-align: center">4.41 &#177; 0.08</td>
      <td style="text-align: center">4.55 &#177; 0.00</td>
      <td style="text-align: center">4.64 &#177; 0.00</td>      
    </tr>
    <tr>
      <td style="text-align: center"><i>GT (Mel + WaveGlow)</i></td>
      <td style="text-align: center">4.00 &#177; 0.09</td>
      <td style="text-align: center">1.007 &#177; 0.18</td>
      <td style="text-align: center">1.022 &#177; 0.060</td>      
    </tr>
    <tr>
      <td style="text-align: center"><i>FastSpeech (Mel + WaveGlow)</i></td>
      <td style="text-align: center">3.84 &#177; 0.08</td>
      <td style="text-align: center">1.052 &#177; 0.05</td>
      <td style="text-align: center">1.03 &#177; 0.28</td>      
    </tr>    
  </tbody>
</table>
<br>
<p class="text">1. Oswald provided little information during his questioning.</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_0.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_0.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_0.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">2. but on arrival he was met by a young sailor with a letter which begged Mr. Gee to go to Heath's house, as the latter was not well.</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_1.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_1.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_1.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">3. and they met with the approval of his professional adviser, the surveyor-general of prisons.</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_2.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_2.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_2.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">4. And he never said anything. So I figured he was one of these people that don't like to talk so I never said any more to him.</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_3.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_3.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_3.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">5. Chief Justice Hughes said in a dissenting opinion that the majority opinion was "a departure from sound principles,"</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_4.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_4.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_4.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">6. but to determine the maximum speed at which it could be fired.</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_5.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_5.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_5.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">7. it would appear to be unlikely that his landlady in Dallas</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_6.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_6.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_6.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">8. Answer: Yes. Question: And you said it was not a good idea to keep this book? Answer: Yes.</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_7.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_7.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_7.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">9. All the allowances of food passed through his hands; he had the control of the poor-box for chance charities,</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_8.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_8.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_8.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">10. Scoggins hurriedly left his seat and hid behind the cab as the man came back toward the corner with gun in hand.</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_9.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_9.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_9.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">11. Three invoices on this clipboard, each dated November twenty-two, were for Scott-Foresman books, located on the first and sixth floors.</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_10.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_10.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_10.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">12. Almost in the same moment in which he hit or pushed me, he vaulted over the back seat and sat on me.</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_11.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_11.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_11.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">13. All that was taken was handed over to Burnett, or a "woman in black" whom Brown met by appointment at Waterloo station.</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_12.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_12.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_12.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">14. the Dallas Police Department forwarded it on December two, nineteen sixty-three.</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_13.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_13.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_13.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">15. But Greenacre in his confession pretended that he and his intended had quarreled over her property or the want of it,</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_14.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_14.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_14.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">16. after which he went to New Zealand, and held an important post in that colony.</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_15.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_15.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_15.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">17. Nebuchadnezzar, or Nebuchadrezzar, as his name should be spelled, was the greatest character in Babylonian history,</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_16.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_16.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_16.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">18. Report of the President's Commission on the Assassination of President Kennedy. The Warren Commission Report. By The President's Commission on the Assassination of President Kennedy.</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_17.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_17.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_17.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">19. is propagated to the muscles by which the body is retracted, and causing them to contract, the act of retraction is brought about.</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_18.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_18.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_18.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">20. Failing any of these methods, seeing that straw was forbidden for fear of fire, they had to be satisfied with a couple of the rugs provided by the city</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_19.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_19.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_19.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">21. that the bullet which missed General Walker was fired from Oswald's rifle to the exclusion of all others, this testimony was considered probative</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_20.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_20.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_20.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">22. the amount of assistance that it can expect from other agencies.</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_21.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_21.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_21.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">23. As the almost inevitable consequence, while the more glaring defects in prison management disappeared,</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_22.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_22.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_22.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">24. One of the photographs taken by Marina Oswald was widely published in newspapers and magazines,</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_23.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_23.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_23.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">25. Jack Brooks, Homer Thornberry, and Albert Thomas joined Clifton C. Carter and the group of special agents protecting the Vice President.</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_24.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_24.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_24.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">26. who would disregard the law and would decide specific cases as I wished them to be decided, I make this answer:</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_25.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_25.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_25.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">27. Howse and his accomplice were arrested; the former was found guilty and sentenced to fifteen years, but the latter was acquitted.</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_26.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_26.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_26.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">28. He could do what he liked with the passbook, and by its adoption, as described as the basis of all entries,</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_27.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_27.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_27.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">29. Lee became very irritable, and sometimes some completely trivial thing would drive him into a rage.</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_28.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_28.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_28.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">30. Other details described by Marina Oswald coincide with facts developed independently of her statements.</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_29.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_29.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_29.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">31. that the FBI took an unduly restrictive view of its responsibilities in preventive intelligence work, prior to the assassination.</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_30.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_30.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_30.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">32. A quantity of quicklime was thrown in with the body to destroy all identification.</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_31.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_31.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_31.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">33. Rub the bottom and sides of a baking-pan with sweet lard or butter. Do this with a bit of clean soft rag or tissue-paper,</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_32.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_32.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_32.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">34. it is never used except for very expensive books, although it would not materially increase the cost in all but the very cheapest.</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_33.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_33.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_33.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">35. Despite this dependence on local authorities, which would be substantially the same on a visit by the President to any large city,</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_34.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_34.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_34.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">36. county, and State law enforcement agencies in their districts.</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_35.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_35.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_35.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">37. It was against common sense to charge her with murdering the only friend she had in the world;</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_36.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_36.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_36.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">38. including a few of major importance.</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_37.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_37.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_37.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">39. It was almost too late.</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_38.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_38.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_38.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">40. the moment too that the condemned man had passed through the debtors' door on to the scaffold the prison had done with him,</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_39.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_39.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_39.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">41. Oswald objected to his mother visiting the apartment</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_40.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_40.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_40.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">42. Morally, it is the greatest menace to our social order.</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_41.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_41.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_41.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">43. and later experience has fully proved the advantage of a judicious system of gratuities for labor;</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_42.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_42.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_42.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">44. The transfer was dated "Friday November twenty-two, 'sixty-three" and was punched in two places by the bus driver.</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_43.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_43.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_43.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">45. and he didn't have any great desire to do so any more because he had run into, as he himself said -- into bureaucracy and red tape, end quote.</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_44.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_44.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_44.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">46. His Marine career was not helped by his attitude</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_45.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_45.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_45.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">47. The first post-mortem indicated death from natural causes,</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_46.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_46.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_46.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">48. A formal and thorough description of the responsibilities of the advance agent is now in preparation by the Service.</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_47.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_47.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_47.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">49. the first by daily services, the latter by the appointment of schoolmasters and instruction in reading and writing.</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_48.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_48.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_48.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">50. The trade of fence, or receiver, therefore, is very nearly as old as the crimes which it so obviously fostered.</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_49.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_49.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_49.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">51. He seemed to prefer the Soviet Union and he spoke highly of Cuba.</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_50.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_50.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_50.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">52. The most important jail act of that early period, however, was the twenty-four George the third c. fifty-four, s. four (seventeen eighty-four)</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_51.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_51.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_51.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">53. Some years later an eye-witness published a graphic account of one of these scenes.</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_52.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_52.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_52.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">54. in order to seek their cooperation in establishing what I may describe as a specific trial period of industrial peace.</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_53.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_53.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_53.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">55. to inspect buildings along the motorcade route since the Secret Service did not normally request or make such a check.</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_54.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_54.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_54.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">56. In the opinion of these experts, it was not possible to estimate the time which elapsed between the placing of the print on the rifle and the date of the lift.</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_55.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_55.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_55.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">57. Everyone agreed that, if there was sufficient time, a motorcade through downtown Dallas would be the best way for the people to see their President.</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_56.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_56.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_56.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">58. On November five, Hosty was traveling near Mrs. Paine's home and took the occasion to stop by to ask whether she had any further information.</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_57.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_57.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_57.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">59. and when the population fell they shut up one half the jail and crowded up the other.</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_58.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_58.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_58.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">60. His captors having thus succeeded in their designs, left him, no doubt to realize the money.</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_59.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_59.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_59.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">61. Chapter four. The Assassin: Part two.</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_60.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_60.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_60.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">62. who not strangely resented the orders issued by the aldermen</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_61.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_61.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_61.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">63. Even the shepherds ceased to graze their sheep there, and the wandering Arabs,</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_62.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_62.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_62.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">64. five. The money from work will possibly be coming. The money will be sent to our post office box. Go to the bank and cash the check.</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_63.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_63.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_63.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">65. Many, like Wainwright, were calm and imperturbable throughout their trying ordeal.</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_64.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_64.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_64.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">66. At the rear on each side of the automobile were small running boards, each designed to hold a Secret Service agent,</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_65.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_65.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_65.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">67. The sermon of this day, whether eloquent or plain, useful or useless, must produce a striking effect at the moment of its delivery.</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_66.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_66.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_66.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">68. Clambering along the roof,</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_67.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_67.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_67.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">69. All this time not one of a numerous body of bystanders offered to assist the policeman in his extremity.</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_68.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_68.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_68.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">70. with convicts of all ages and characters, to render it next to impossible but that, with the obliteration of all sense of self-respect,</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_69.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_69.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_69.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">71. By the same forcible means I was compelled to quit England, and to trust myself to the protection of this person,</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_70.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_70.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_70.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">72. inside the jail was Colonel Frazer, the chief commissioner of the city police, and at no great distance, although in the background,</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_71.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_71.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_71.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">73. There should be at least a full and fair trial given to these means of ending industrial warfare;</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_72.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_72.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_72.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">74. kept open house, so to speak, and entertained daily within the walls a select party of the most noted thieves in London.</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_73.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_73.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_73.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">75. The latter material expresses great hostility to both communism and capitalism. He wrote, that to a person knowing both of those systems, quote,</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_74.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_74.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_74.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">76. The man was dressed in faded blue color khaki work clothes, a brown shirt, and some kind of work jacket that almost matched his pants.</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_75.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_75.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_75.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">77. Oswald told his brother, quote, on what terms I want this arrangement, end quote. He advised Robert that: one.</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_76.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_76.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_76.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">78. the difficulty of access, and the admitted necessity of giving architectural importance to this the national model prison.</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_77.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_77.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_77.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">79. On the other hand he also told her that he wished his mother had been more firm with him in her attempts to get him to return to school.</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_78.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_78.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_78.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">80. Oswald never asked Mrs. Paine about the use of curtain rods,</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_79.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_79.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_79.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">81. the earliest estimates would still have permitted Oswald to leave the building by twelve:thirty-three.</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_80.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_80.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_80.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">82. This passbook, when not at the bank, was in the exclusive custody of Watts.</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_81.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_81.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_81.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">83. who advised that Mr. Johnson take the Presidential oath of office before the plane left Dallas.</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_82.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_82.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_82.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">84. But the welfare of the United States, and indeed of the Constitution itself, is what we all must think about first.</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_83.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_83.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_83.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">85. Stombaugh testified that the colors, shades, and twist of the fibers found in the tuft on the rifle matched those in Oswald's shirt.</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_84.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_84.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_84.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">86. as being the left palmprint and right index fingerprint of Lee Harvey Oswald.</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_85.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_85.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_85.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">87. who wrote to the 'Times,' saying that he believed "a sight so inconceivably awful</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_86.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_86.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_86.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">88. for it is here that oxidation occurs and the need for a renewal of matter and energy consequently arises.</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_87.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_87.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_87.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">89. He picked Oswald from the lineup as the man who had boarded the bus at the, quote, lower end of town on Elm around Houston, end quote,</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_88.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_88.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_88.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">90. She added that while he helped her as he had done before, he became more of a recluse, that, quote,</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_89.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_89.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_89.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">91. Prompted by these dismaying statistics, the Commission has inquired into the problems and methods of Presidential protection in effect</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_90.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_90.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_90.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">92. but there is a system for the immediate notification of the Secret Service by the confining institution when a subject is released or escapes.</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_91.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_91.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_91.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">93. Where it had lain was a yawning gulf or trap sufficient to do for the whole body of police engaged in the capture.</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_92.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_92.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_92.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">94. The next word about Oswald's location was a communication from the CIA to the FBI on October ten,</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_93.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_93.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_93.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">95. and he was soon approached by the police. Almost directly he was questioned he made a clean breast of the whole affair.</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_94.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_94.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_94.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">96. The change of one vote would have thrown all the affairs of this great Nation back into hopeless chaos.</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_95.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_95.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_95.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">97. in the territory of the Secret Service regional office which includes Dallas and Fort Worth.</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_96.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_96.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_96.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">98. Hardwicke, or "Ralph," appealed to Saward in his difficulty</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_97.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_97.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_97.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">99. Liaison With Local Law Enforcement Agencies</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_98.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_98.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_98.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


<p class="text">100. had been sold out under a forged power of attorney.</p>
<table>
  <tbody>
    <tr>
      <td style="text-align: center"><b>Predicted</b></td>
      <td style="text-align: center"><b>Ground Truth Synthesized by Waveglow</b></td>
      <td style="text-align: center"><b>Ground Truth</b></td>
    </tr>
    <tr>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_audios_by_waveglow/test_texts_ljspeech_v1_99.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/synthesized_target_audios_by_waveglow/test_texts_ljspeech_v1_99.mel_synthesis.wav" controls="" preload=""></audio></td>
      <td style="text-align: center"><audio src="ljspeech_test_audios/target_audios/test_texts_ljspeech_target_v1_99.mel_synthesis.wav" controls="" preload=""></audio></td>
    </tr>
  </tbody>
</table>


