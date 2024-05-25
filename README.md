<h1>EX-TranslateXSummary-Robot</h1>

<p>This Python program is designed to process audio content from files or YouTube videos. It provides a comprehensive set of tools for extracting, translating, and summarizing audio content.</p>

<h2>Features</h2>

<ul>
  <li><b>Extract Text from Audio</b>: Utilizes the Whisper model to extract text from audio files.</li>
  <li><b>Translate Text</b>: Translates extracted text to the user-selected target language using the deep-translator library.</li>
  <li><b>Summarize Text</b>: Generates a summary of the translated text using OpenAI's GPT model.</li>
  <li><b>Supports YouTube Videos</b>: Allows users to provide YouTube video URLs for audio processing.</li>
</ul>

<h2>How to Use</h2>

<ol>
  <li>Clone this repository to your local machine.</li>
  <li>Install the required dependencies listed in <code>requirements.txt</code>.</li>
  <li>Run the <code>main.py</code> script.</li>
  <li>Choose whether to upload a local audio file or provide a YouTube video URL.</li>
  <li>Follow the prompts to select the target language and view the translated text and summary.</li>
</ol>

<h2>Dependencies</h2>

<ul>
  <li>openai</li>
  <li>pytube</li>
  <li>whisper</li>
  <li>pandas</li>
  <li>requests</li>
  <li>deep-translator</li>
  <li>moviepy</li>
</ul>

<h2>License</h2>

<p>This project is licensed under the MIT License - see the <a href="LICENSE">LICENSE</a> file for details.</p>
