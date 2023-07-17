# Creates a silent WAV file with the specified duration and saves it to the given filename.

## pip install silentwav 

#### Tested against Windows 10 / Python 3.10 / Anaconda 



```python
Creates a silent WAV file with the specified duration and saves it to the given filename.

Parameters:
	filename (str): The path and filename of the WAV file to be created.
	duration (int | float): The duration of the silent WAV file in seconds.
	sample_rate (int, optional): The number of samples per second. Defaults to 44100.
	num_channels (int, optional): The number of audio channels. Defaults to 1 (mono).
	sample_width (int, optional): The size of each audio sample in bytes. Defaults to 2 bytes (16-bit audio).
	compression_type (str, optional): The type of compression for the WAV file. Defaults to "NONE".
	compression_name (str, optional): A description of the compression used. Defaults to "not compressed".

Returns:
	None: This function does not return any value but creates a silent WAV file and saves it to the specified filename.

Example:
	from silentwav import create_silent_wav
	# Creates a 60-second silent WAV file named "c:\\silent_file.wav"
	create_silent_wav("c:\\silent_file.wav", duration=60)


```