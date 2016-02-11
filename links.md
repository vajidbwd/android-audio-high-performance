---
layout: page
title: Links to audio resources
permalink: /links.html
is_site_nav_category: false
site_nav_category: links
site_nav_category_order: 5
---

<!--
    Copyright 2015 The Android Open Source Project

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
-->

<table>

<tr>
  <th>Area</th>
  <th>Title</th>
  <th>Notes</th>
</tr>

<tr>
  <td rowspan="5">Apps with<br />source code</td>
  <td><a
href="https://github.com/gkasten/high-performance-audio/tree/master/audio-buffer-size">audio-buffer-size</a>
      (source)<br />
      <!-- https://code.google.com/p/high-performance-audio/source/browse/ -->
      <a href="https://play.google.com/store/apps/details?id=com.levien.audiobuffersize">audio-buffer-size</a>
      (binary)
  </td>
  <td>estimates hardware buffer size emperically</td>
</tr>

<tr>
  <td><a href="https://github.com/gkasten/drrickorang/tree/master/LoopbackApp">Dr. Rick O'Rang Loopback</a>
      (source)<br />
      <a href="https://play.google.com/store/apps/details?id=org.drrickorang.loopback">Dr. Rick O'Rang loopback</a>
      (binary)
  </td>
  <td>measures round-trip latency</td>
</tr>

<tr>
  <td><a href="https://github.com/gkasten/high-performance-audio/tree/master/GrandCanyon">Grand Canyon</a></td>
  <td>demonstration of audio latency</td>
</tr>

<tr>
  <td><a href="https://github.com/google/music-synthesizer-for-android">Music Synthesizer for Android</a></td>
    <!-- https://code.google.com/p/music-synthesizer-for-android/ -->
  <td>by Raph Levien</td>
</tr>

<tr>
  <td><a href="https://github.com/superpoweredSDK/SuperpoweredLatency">SuperPowered Latency Test</a></td>
  <td>Tests round trip audio latency by outputting a sine wave and waiting for signal to arrive at the microphone input.</td>
</tr>

<tr>
  <td rowspan="2">Audio</td>
  <td><a href="https://source.android.com/devices/audio/terminology.html">Audio Terminology</a></td>
  <td rowspan="2"></td>
</tr>
<tr>
  <td><a href="https://source.android.com/devices/audio/src.html">Sample Rate Conversion</a></td>
</tr>

<tr>
  <td rowspan="3">Compatibility</td>
  <td><a href="https://source.android.com/compatibility/">Android Compatibility</a></td>
  <td rowspan="3"></td>
</tr>
<tr>
  <td><a href="https://source.android.com/compatibility/android-cdd.pdf">CDD</a></td>
</tr>
<tr>
  <td><a href="https://source.android.com/accessories/headset/specification.html">Wired Audio Headset Specification (v1.1)</a></td>
</tr>

<tr>
  <td rowspan="3">Encoded audio</td>
  <td><a href="http://developer.android.com/guide/appendix/media-formats.html">Supported Media Formats</a></td>
  <td></td>
</tr>
<tr>
  <td><a href="http://developer.android.com/reference/android/media/MediaCodec.html">MediaCodec</a></td>
  <td>recommended SDK API for encoding and decoding</td>
</tr>
<tr>
  <td>
  <a href="{{site.baseurl}}/guides/opensl_es.html#decode-audio-to-pcm">Decoding audio to PCM section of OpenSL ES guide</a></td>
  <td>deprecated NDK API for decoding</td>
</tr>

<tr>
  <td rowspan="2">General</td>
  <td><a href="https://developers.google.com/">Google Developers</a></td>
  <td rowspan="2">General developer resources<br />(not specific to audio)</td>
</tr>
<tr>
  <td><a href="http://developer.android.com/support.html">Developer Support Resources</a></td>
</tr>

<tr>
  <td rowspan="7">Latency</td>
  <td><a href="https://source.android.com/devices/audio/latency_app.html">Audio Latency for App Developers</a></td>
  <td rowspan="7"></td>
</tr>
<tr>
  <td><a href="https://source.android.com/devices/audio/latency_measurements.html">Audio Latency Measurements</a></td>
</tr>
<tr>
  <td><a href="https://source.android.com/devices/audio/latency.html">Audio Latency</a></td>
</tr>
<tr>
  <td><a href="https://source.android.com/devices/audio/warmup.html">Audio Warmup</a></td>
</tr>
<tr>
  <td><a href="http://en.wikipedia.org/wiki/Latency_%28audio%29">Latency (audio)</a> at Wikipedia</td>
</tr>
<tr>
  <td><a href="http://en.wikipedia.org/wiki/Round-trip_delay_time">Round-trip delay time</a> at Wikipedia</td>
</tr>
<tr>
  <td><a href="http://developer.android.com/reference/android/media/AudioManager.html#getProperty%28java.lang.String%29">API level 17 native audio configuration</a></p>
</tr>

<tr>
  <td rowspan="5">MIDI</td>
  <td><a href="https://developer.android.com/reference/android/media/midi/package-summary.html">android.media.midi package</a></td>
  <td>Android MIDI User Guide</td>
</tr>
<tr>
  <td><a href="https://source.android.com/devices/audio/midi.html">MIDI</a></td>
  <td>MIDI implementation guide<br />for OEMs and SoC vendors</td>
</tr>
<tr>
  <td><a href="https://source.android.com/devices/audio/midi_test.html">MIDI Test Procedure</a></td>
  <td>validate correct implementation<br />of MIDI on your device</td>
</tr>
<tr>
  <td><a href="https://groups.google.com/forum/#!forum/android-midi">android-midi</a></td>
  <td>discussion group</td>
</tr>
<tr>
  <td><a href="http://www.midi.org/aboutmidi/android.php">Android OS MIDI and Audio</a></td>
  <td>at MMA</td>
</tr>

<tr>
  <td rowspan="6">NDK</td>
  <td><a href="https://developer.android.com/tools/sdk/ndk/index.html">Android NDK</a></td>
  <td>at SDK</td>
</tr>
<tr>
  <td><a href="https://developer.android.com/ndk/index.html">Android NDK</a></td>
  <td>NDK home page</td>
</tr>
<tr>
  <td><a href="https://developer.android.com/ndk/guides/index.html">Getting Started with the NDK</a></td>
  <td></td>
</tr>
<tr>
  <td><a href="https://developer.android.com/ndk/reference/index.html">API Reference</a></td>
  <td>omits audio; see OpenSL ES</td>
</tr>
<tr>
  <td><a href="https://groups.google.com/forum/#!forum/android-ndk">android-ndk</a></td>
  <td>discussion group</td>
</tr>
<tr>
  <td><a href="https://android.googlesource.com/platform/ndk">post release updates to NDK</a></td>
  <td>such as documentation</p>
</tr>

<tr>
  <td rowspan="2">OpenSL ES</td>
  <td>
    <code>
    &lt;NDK_ROOT&gt;/docs/Additional_library_docs/<br/>opensles/index.html
    </code>
  </td>
  <td>After installing Android NDK, the native audio documentation is here</td>
</tr>
<tr>
  <td><a href="{{site.baseurl}}/guides/opensl_es.html">OpenSL ES for Android</a></td>
  <td>or you can find it online here</td>
</tr>

<tr>
  <td>Predictable<br />performance</td>
  <td><a href="https://source.android.com/devices/audio/avoiding_pi.html">Avoiding Priority Inversion</a></td>
  <td></td>
</tr>

<tr>
  <td rowspan="2">Sample code</td>
  <td><a href="https://developer.android.com/ndk/samples/index.html">Samples: Overview</a></td>
  <td></td>
</tr>
<tr>
  <td><a href="https://developer.android.com/ndk/samples/walkthroughs.html">Samples: Walkthroughs</a></td>
  <td>incomplete</td>
</tr>

<tr>
  <td rowspan="4">SDK</td>
  <td><a href="http://developer.android.com/guide/topics/media/audio-capture.html">Audio Capture</a></td>
  <td>for audio</td>
</tr>

<tr>
  <td><a href="http://developer.android.com/guide/topics/media/index.html">Media and Camera</a></td>
  <td rowspan="3">media includes video and audio</td>
</tr>
<tr>
  <td><a href="http://developer.android.com/guide/topics/media/mediaplayer.html">Media Playback</a></td>
</tr>
<tr>
  <td><a href="http://developer.android.com/reference/android/media/package-summary.html">android.media package</a></td>
</tr>
<tr>
  <td rowspan="2">USB digital audio</td>
  <td><a href="https://source.android.com/devices/audio/usb.html">USB Digital Audio</a></td>
  <td>implementation guide</td>
</tr>

<tr>
  <td><a href="https://support.google.com/nexus/answer/6127700">Record and play back audio using USB host mode</a></td>
  <td>for users</td>
</tr>

<tr>
  <td rowspan="5">Videos</td>
  <td><a href="https://www.youtube.com/watch?v=PnDK17zP9BI">Audio latency: buffer sizes</a>
    (Youtube)</td>
  <td>Google I/O 2015 100 Days of Google Dev with<br />Glenn Kasten &amp; Ian Ni-Lewis</td>
</tr>
<tr>
  <td><a href="https://www.youtube.com/watch?v=6Dl6BdrA-sQ">Sample rates and resampling:<br />Why can't we all just agree?</a>
    (Youtube)</td>
  <td>Google I/O 2014 DevBytes<br />with Andy Hung</td>
</tr>
<tr>
  <td><a href="https://www.youtube.com/watch?v=sIcieUqMml8">Will it float?<br />The glory and shame of floating-point audio</a>
    (Youtube)</td>
  <td>Google I/O 2014 DevBytes<br />with Glenn Kasten</td>
</tr>
<tr>
  <td><a href="https://www.youtube.com/watch?v=92fgcUNCHic">Building great multi-media experiences on Android</a>
    (Youtube)</td>
  <td>Google I/O 2014 session<br />with the Android media team; includes segments on<br />audio, video, &amp; camera</td>
</tr>
<tr>
  <td><a href="http://www.youtube.com/watch?v=d3kfEeMZ65c">High performance audio</a> (Youtube)</td>
  <td>Google I/O 2013 session with<br />
    Glenn Kasten, Raph Levien, &amp; Ian Ni-Lewis</td>
</tr>
<tr>
  <td>Wrappers</td>
  <td><a href="https://github.com/nettoyeurny/opensl_stream">opensl_stream library</a></td>
  <td>wraps OpenSL ES to present<br />a simplified API</td>
</tr>

</table>