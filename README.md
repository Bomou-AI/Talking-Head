# Talking Head
AI Talking Head: create video from plain text or audio file in minutes, support up to 100+ languages and 350+ voice models.

Create your custom Talking Head for free.
https://en.bomou.com/avatars/

虚拟主播制作中文版 https://bomou.com/cn/va/

# Text to Video API:

<pre>

https://en.bomou.com/avatars/api?token={your token}
&model_id={ your custom AI avatar id}
&template_id={your custom AI avatar template/style id }
&speaker_id={ the accent model id}
&speaker_style={assistant,chat,customerservice,newscast,affectionate,angry,calm,cheerful,disgruntled,fearful,gentle,lyrical,sad,serious,poetry-reading }
&speaker_speed={ slow or fast level: -10 to 10}
&speaker_volume={ low or high level: -10 to 10}
&speaker_tone={ pitch of the tone: -10 to 10 }
&text={ video script, plain text or with some tags}
&pos={the avatar position/scale on the background image or video}
&bgurl={ background image or video url}
&callback={callback this url at the end of video synthesis, video is ready for download}

</pre>

# Audio to Video API:

<pre>

https://en.bomou.com/avatars/api?token={your token}
&model_id={ your custom AI avatar id}
&template_id={your custom AI avatar template/style id }
&audio={audio url}
&pos={the avatar position/scale on the background image or video}
&bgurl={ background image or video url}
&callback={callback this url at the end of video synthesis, video is ready for download}

</pre>


# Callback URL:

<pre>

https://yourcallbackurl?downloadurl={the download url for generated video }

</pre>
