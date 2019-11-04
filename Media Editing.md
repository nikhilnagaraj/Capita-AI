# Media editing snippets

FFMpeg must be available on your system.

## Snipping Audio & Video

```shell

ffmpeg -ss <start_time_in_seconds> -t <number_of_seconds> <input_file_name_with_extension> <output_file_name_with_extension>

```

## Converting wav audio to midi

>Not Recommended. Sound quality is terrible.

Waon must be installed on your system.

```shell
waon -i <input_wav_file> -o <output_name>.mid

```
