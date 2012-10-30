Anymote-for-Java
================

<p>The Anymote-for-Java library implements the Google TV Pairing and Anymote protocols in pure Java.</p>

<p>Google open sourced the implementations of their software to allow mobile devices to communicate with Google TV devices. 
The Google TV Pairing Protocol is used to pair sessions between mobile devices and Google TV.
The Anymote Protocol is a messaging protocol that applications on a remote device use to communicate with Google TV. 
Anymote supports commands that are like those of a physical remote control.</p>

<p>If you want to write an app that communicates with Google TV devices you can either use the source code of the <a href="https://code.google.com/p/google-tv-remote/">Google TV 
Remote app</a> or you can use the <a href="https://code.google.com/p/googletv-android-samples/source/browse/#git%2FAnymoteLibrary">Anymote Library</a>. Both of these are based on Android. </p>

<p>The Anymote-for-Java library has the following advantages:
<ol>
<li>Not dependent on Android. Any 1.6 JRE on any platform will work.</li>
<li>Paired devices are remembered. The Google Anymote library requires the pairing PIN to be entered for each session.</li>
<li>The user interface is externalized and replaceable. The Google Anymote library has the Android user interface embedded.</li>
</ol>
</p>

<p>Anymote-for-Java is based on the Google Anymote Library code, but all Android dependencies have been replaced with pure Java logic. 
Platform-specific logic like creating files or getting the network configuration is isolated in the Platform class.</p>

<p>Run com.entertailion.java.anymote.test.Example to see the library in action.</p>

<p>References:
<ul>
<li><a href="https://developers.google.com/tv/remote/docs/pairing">Google TV Pairing Protocol</a></li>
<li><a href="https://code.google.com/p/anymote-protocol/">Anymote Protocol</a></li>
<li><a href="https://developers.google.com/tv/remote/docs/developing">Building Second-screen Applications for Google TV</a></li>
</ul>
</p>





