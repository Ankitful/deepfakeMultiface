here is command line arguments for this program
<br>
--help  showing all arguments
<br>
'-s', '--source',                          'select an source image'
<br>
-t', '--target',                           'select an target image or video'
<br>
'-o', '--output',                          'select output file or directory'
<br>
'--frame-processor',                       'frame processors (choices: face_swapper, face_enhancer, ...)', default=['face_swapper'], nargs='+')
<br>
'--keep-fps',                              'keep target fps'
<br>
'--keep-frames',                           'keep temporary frames'
<br>
'--skip-audio',                            'skip target audio'
<br>
'--many-faces',                            'process every face'
<br>
'--reference-face-position',               'position of the reference face'
<br>
'--reference-frame-number',                'number of the reference frame'
<br>
'--similar-face-distance',                 'face distance used for recognition'
<br>
'--temp-frame-format',                     'image format used for frame extraction'
<br>
'--temp-frame-quality',                    'image quality used for frame extraction'
<br>
'--output-video-encoder',                  'encoder used for the output video'
<br>
'--output-video-quality',                  'quality used for the output video'
<br>
'--max-memory',                            'maximum amount of RAM in GB'
<br>
'--execution-provider',                    'available execution provider (choices: cpu, ...)',default=['cpu'], 
<br>
'--execution-threads',                     'number of execution threads', type=int,
<br>
'-v', '--version', action='version', version=f'{roop.metadata.name} {roop.metadata.version}')
