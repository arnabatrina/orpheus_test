
#python gguf_orpheus.py --text "Your text here" --voice tara --output "output.wav"
#Add whatever you want the ouput with like we have different emotions like <laugh>, <chuckle>, <sigh>, <cough>, <sniffle>, <groan>, <yawn>, <gasp> etc.
#This is a simple script to generate speech using the Orpheus model via the LM Studio API.
# It allows you to specify the text, voice, and output file, and can also list available voices.
# The script uses the requests library to interact with the API and sounddevice for audio playback.
#python gguf_orpheus.py --text "Hello! This is just the Orpheus test for emotions like I can Laugh<laugh>and I can be sigh<sigh> or even I can Cough like this<Cough> and there is a lot I can do guys just let me know right have a nice day you all" --voice tara --output "test.wav"
