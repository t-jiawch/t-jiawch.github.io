<html><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8">

<title>Audio Samples</title>
<style>html, * {-webkit-user-select:text!important; -moz-user-select:text!important;}</style></head>

<body style="text-align: left;">
<h1>Singing Demos for "XiaoiceSing: A High-Quality and Integrated Singing Voice Synthesis System"</h1>

<h4 style="display:inline">Authors: </h4> <p style="display:inline">Peiling Lu, Jie Wu, Jian Luan, Xu Tan, Li Zhou</p>
<br>
<br>
<h4 style="display:inline">Abstract: </h4> <p style="display:inline">This paper presents XiaoiceSing, a high-quality singing voice synthesis system which employs an integrated network for spectrum, F0 and duration modeling. We follow the main architecture of FastSpeech while proposing some singing-specific design: 1) Besides phoneme ID and position encoding, features from musical score (e.g.note pitch and length) are also added. 2) To attenuate off-key issues, we add a residual connection in F0 prediction. 3) In addition to the duration loss of each phoneme, the duration of all the phonemes in a musical note is accumulated to calculate the syllable duration loss for rhythm enhancement. Experiment results show that XiaoiceSing outperforms the baseline system of convolutional neural networks by 1.44 MOS on sound quality, 1.18 on pronunciation accuracy and 1.38 on naturalness respectively. In two A/B tests, the proposed F0 and duration modeling methods achieve 97.3% and 84.3% preference rate over baseline respectively, which demonstrates the overwhelming advantages of XiaoiceSing.</p>


<hr>
<p>Below is the subjective evaluation samples for our Interspeech2020 paper.</p>
<p><strong>Note:</strong> Please ensure your web browser supports wav audio format. You can choose Microsoft Edge, Google Chrome, Firefox, Opera and Safari.</p>
<p>&nbsp;</p>
<h3>Subjective Evaluation Singing Demo</h3>

<table width="81%" border="1">
  <tbody>
    <tr>
      <th width="22%" style="text-align: center" scope="col">Recording</th>
      <th width="26%" style="text-align: center" scope="col">Baseline</th>
      <th width="26%" style="text-align: center" scope="col">XiaoiceSing</th>
    </tr>
	
    <tr>
      <td width="26%" style="text-align: center"><audio controls="">
        <source src="audio/Recording1.wav" type="audio/wav">
      </audio></td>
      <td width="26%" style="text-align: center"><audio controls="">
        <source src="audio/DNN1.wav" type="audio/wav">
      </audio></td>
      <td width="26%" style="text-align: center"><audio controls="">
        <source src="audio/Fastspeech1.wav" type="audio/wav">
      </audio></td>
    </tr>

    <tr>
      <td width="26%" style="text-align: center"><audio controls="">
        <source src="audio/Recording2.wav" type="audio/wav">
      </audio></td>
      <td width="26%" style="text-align: center"><audio controls="">
        <source src="audio/DNN2.wav" type="audio/wav">
      </audio></td>
      <td width="26%" style="text-align: center"><audio controls="">
        <source src="audio/Fastspeech2.wav" type="audio/wav">
      </audio></td>
    </tr>

    <tr>
      <td width="26%" style="text-align: center"><audio controls="">
        <source src="audio/Recording3.wav" type="audio/wav">
      </audio></td>
      <td width="26%" style="text-align: center"><audio controls="">
        <source src="audio/DNN3.wav" type="audio/wav">
      </audio></td>
      <td width="26%" style="text-align: center"><audio controls="">
        <source src="audio/Fastspeech3.wav" type="audio/wav">
      </audio></td>
    </tr>

    <tr>
      <td width="26%" style="text-align: center"><audio controls="">
        <source src="audio/Recording4.wav" type="audio/wav">
      </audio></td>
      <td width="26%" style="text-align: center"><audio controls="">
        <source src="audio/DNN4.wav" type="audio/wav">
      </audio></td>
      <td width="26%" style="text-align: center"><audio controls="">
        <source src="audio/Fastspeech4.wav" type="audio/wav">
      </audio></td>
    </tr>

    <tr>
      <td width="26%" style="text-align: center"><audio controls="">
        <source src="audio/Recording5.wav" type="audio/wav">
      </audio></td>
      <td width="26%" style="text-align: center"><audio controls="">
        <source src="audio/DNN5.wav" type="audio/wav">
      </audio></td>
      <td width="26%" style="text-align: center"><audio controls="">
        <source src="audio/Fastspeech5.wav" type="audio/wav">
      </audio></td>
    </tr>
	
  </tbody>
</table></body></html>
