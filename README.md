### Hi there 👋
### Find here some of my personnal, free and open source software repositories:
<hr>

### ⚡ WindowsAudioSession 1.0 binaries are now available here:

https://github.com/franck-gaspoz/WindowsAudioSessionSample/releases/download/v1.0/WindowsAudioSession_1.0.7z

unzip anywhere and run WindowsAudioSession.exe. Select your audio device in the top left list and press the button 'Start'

### ⚡ <u>Tensorflow Keras deep learning samples & image prediction</u>

A few samples to demonstrates the use of tensorflow and keras, throught basic samples and for image recognition, with a python WEB API that serves the image recognition functionnality

<table width="100%" style="width:100%;border:none" border="0">
<tr>
<td>
<img src="https://raw.githubusercontent.com/franck-gaspoz/TensorflowKeras_DeepLearning_Samples/master/doc/server.png" width="100%" align="center" style="margin-left:auto;margin-right:auto" alt="">
<p align="center"> 
<i>running Uvicorn FastAPI serving the image recognition functionnality using VGG16</i>
</p>
</td>
<td>
<img src="https://raw.githubusercontent.com/franck-gaspoz/TensorflowKeras_DeepLearning_Samples/master/doc/CNN-VGG-mug.jpg" width="170px" align="center" style="margin-left:auto;margin-right:auto" alt="">
<p align="center">
<i>image to be classified</i>
</p>
</td>
<td>
<img src="https://raw.githubusercontent.com/franck-gaspoz/TensorflowKeras_DeepLearning_Samples/master/doc/mug-prediction.png" width="100%" align="center" style="margin-left:auto;margin-right:auto" alt="">
<p align="center">
<i>the classification results given by the HTTP query JSon response</i>
</p>              
</td>
</tr>
</table>

- read the project README @ [https://github.com/franck-gaspoz/TensorflowKeras_DeepLearning_Samples/blob/master/README.md](https://github.com/franck-gaspoz/TensorflowKeras_DeepLearning_Samples/blob/master/README.md)

### ⚡ <u>Windows Audio Session (WASAPI) sample:</u>

A sample of usage of Windows Audio Session WASAPI using BASS.NET - WPF C# .NET Framework 4.8

- colored bars (vu-meters) showing captured device sound FFT , Sound Level and sound wave

<p align="center">
<img src="https://raw.githubusercontent.com/franck-gaspoz/WindowsAudioSessionSample/main/Doc/windows-audio-session-sample3.gif"  width="70%" align="center" style="margin-left:auto;margin-right:auto" alt="a FFT having 512 bars + FFT with 16 bars and peak bars + stereo sound level">
<br>
<i>a FFT having 512 bars + FFT with 16 bars and peak bars + stereo sound level + sound wave</i>
</p>

Run the project, select your audio device, and this tool will listen to the device internal output and animates some of the sound properties. The library BASS.NET is used to interface C# with the WASAPI Windows library.

Clean architecture & SOLID approach: complete discoupling between data,data providers,data transformers,ui controls,drawers,view models,application logic. Relying on the patterns MVVM, Command and Chain of responsability. Implements several importants aspects of WPF programming:
- User Controls, Resources/Styles, Converters, View Models, Data annotations, Data validators, Data binding, Commands, Visual Drawings
  

- read the project README @ [https://github.com/franck-gaspoz/WindowsAudioSessionSample/blob/main/README.md](https://github.com/franck-gaspoz/WindowsAudioSessionSample/blob/main/README.md)

### ⚡ <u>Orbital Shell:</u>
Multi-plateform (**windows, linux, macos, arm**) command shell (according to .Net Core supported platforms and APIs compatibilities), inspired by <b><i>bash</i></b> and **POSIX** recommendations.<br><br>It provides any usual bash shell feature (even if modernized) and 'user friendly' syntaxes allowing to access (get/set/call) C# objects.<br><br>Developed using **C# 8 .NET 5.0 - compatible with modules and libraries targeting .NET Core 3.1 and .NET Standard 2.1** , developped using GitHub CI/CD (build,nuget packaging,storage)<br>
This shell integrates the <u>most usefull shell commands</u>, and is intented to be extended by coding new commands or downloading new commands modules within a repository of modules. Of course it can be enterly customized by using the features integrated to the shell (<u>scripts, functions, commands, aliases, settings, parametrization,...</u>). Having a strong <u>ANSI/VT-100-220-300-500</u> support, it provides structured and colorized display of data and information (support of <u>ASCII, Unicode and 24 bits colors</u>). Includes a <u>Web API</u> for support of remote shell<br><br>
<p align="center">
<img src="https://raw.githubusercontent.com/OrbitalShell/Orbital-Shell-Assets/9aa1c9b4e36fae70f686d8b6e4cab4f81d59a6df/1.jpg" width="70%" align="center" style="margin-left:auto;margin-right:auto">
<br><br>
orbsh running in windows terminal console
</p>
<b>Contribute :</b><br>

We are looking for **collaborators** (currently there is **13 members**) to help evolving this tool !
  - read the project README @ [https://github.com/OrbitalShell/orbital-shell/blob/master/README.md](https://github.com/OrbitalShell/Orbital-Shell/blob/master/README.md)
  - visit the project's web site @ [https://OrbitalShell.github.io/orbital-shell/](https://orbitalshell.github.io/OrbitalShell/)
  - go to the project main repository (6 at all) @ [https://github.com/OrbitalShell/orbital-shell/](https://github.com/OrbitalShell/Orbital-Shell/)

### ⚡ <u>GIS Tools - Map Viewer (WPF) :</u>

Part of a new sery of GIS tools (Geographical Information Systems) that I recently started to develop, this software is a map viewer / downloader, that is a re-build and retro-engineering of the existing WEB site of the French BRGM (National Geographical Service) as a WPF Desktop application, allowing to introduce many improvments and functionnalities to the aging web site. Uses the DotSpatial.Projections library for geological coordinates computation
<p align="center">
<img src="https://raw.githubusercontent.com/franck-gaspoz/franck-gaspoz/ca08439e496de48a125a99865d36332902fb7fc1/2021-11-24%2022_44_56-GIS%20Map%20Viewer.png" width="60%" align="center" style="margin-left:auto;margin-right:auto">
<br><br>
GIS Map Viewer <i>(currently Private, will be opened soon)</i>
</p>

### ⚡ <u>Widget Dock (WPF) :</u>

<p align="center">
<img src="https://raw.githubusercontent.com/franck-gaspoz/WidgetDockXTreme/master/Doc/preview.png" width="60%" align="center" style="margin-left:auto;margin-right:auto"/>
<br><br>
provided with a <a href="https://github.com/franck-gaspoz/WidgetDockXTreme/tree/master/Doc/Design%20And%20Implementation%20-%20Tutorial">dev tutorial</a>
</p>

### ⚡ <u>WPF Utilities (WPF) :</u>

<p align="center">
<img src="https://raw.githubusercontent.com/franck-gaspoz/WPFUtilities/main/Doc/app-sample-preview.png" width="70%" align="center" style="margin-left:auto;margin-right:auto"/>
<br><br>
WPF made simple with a SOLID approach for MVVM<br>
a complete set of essential components
</p>
🚧 still under construction 🚧 nuget available 🚧

- read the project README @ [https://github.com/franck-gaspoz/WPFUtilities/blob/main/README.md](https://github.com/franck-gaspoz/WPFUtilities/blob/main/README.md)

### ⚡ <u>Other works below</u>

- parsing any language with ANTLR C#
- view model base implementation for WPF
- google (free) translator api
- command pattern extension
- mantisBT web server api (Swagger/OpenAPI)
- multi modal MVVM model validation
- various CLI tools and libraries (WPF,Log,..)


## ⚡ About me

[![Github](https://img.shields.io/github/followers/franck-gaspoz?label=Follow&style=social)](https://github.com/franck-gaspoz)
[![Linkedin](https://img.shields.io/badge/-franck%20gaspoz-blue?style=flat-square&logo=linkedin&logoColor=white&link=)](https://www.linkedin.com/in/franckgaspoz/)
[![Mail](https://img.shields.io/badge/-franck.gaspoz@gmail.com-gray?style=flat-square&logo=gmail&logoColor=red&link=)](mailto:franck.gaspoz@gmail.com)
<a href="https://franckgaspoz.fr/en" target="_new"><img src="https://img.shields.io/badge/web%20site-https%3A%2F%2Ffranckgaspoz.fr-brightgreen"></a>
<img src="https://visitor-badge.laobi.icu/badge?page_id=franck-gaspoz">

<br/>

<div align="center">

<img height="180em"  src="https://github-readme-streak-stats.herokuapp.com/?user=franck-gaspoz&theme=gotham&hide_border=true" />
<img height="180em"  src="https://github-readme-stats.vercel.app/api?username=franck-gaspoz&show_icons=true&theme=blue-green" />

</div>
  
<!--
**OrbitalShell/OrbitalShell** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
