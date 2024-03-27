here is command line arguments for this program
--help  showing all arguments
'-s', '--source',                          'select an source image'
-t', '--target',                           'select an target image or video'
'-o', '--output',                          'select output file or directory'
'--frame-processor',                       'frame processors (choices: face_swapper, face_enhancer, ...)', default=['face_swapper'], nargs='+')
'--keep-fps',                              'keep target fps'
'--keep-frames',                           'keep temporary frames'
'--skip-audio',                            'skip target audio'
'--many-faces',                            'process every face'
'--reference-face-position',               'position of the reference face'
'--reference-frame-number',                'number of the reference frame'
'--similar-face-distance',                 'face distance used for recognition'
'--temp-frame-format',                     'image format used for frame extraction'
'--temp-frame-quality',                    'image quality used for frame extraction'
'--output-video-encoder',                  'encoder used for the output video'
'--output-video-quality',                  'quality used for the output video'
'--max-memory',                            'maximum amount of RAM in GB'
'--execution-provider',                    'available execution provider (choices: cpu, ...)',default=['cpu'], 
'--execution-threads',                     'number of execution threads', type=int,
'-v', '--version', action='version', version=f'{roop.metadata.name} {roop.metadata.version}')
