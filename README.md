# Inspiration :star:
We saw a call center getting a lot of calls in a day and it made us wonder how emergency services respond to calls. So we thought of making a tool that can help them analyze the call and give all the details instead of looking for everything manually.

# What it does :rotating_light: 
- Audio Transcription :microphone:: Quickly convert spoken words from emergency calls into text for easy understanding.
- Location extraction :map: : to get the precise location of the places that are mentioned in the call
- Summarization  :clipboard: : Get a concise summary of the emergency call to assess the situation at a glance.
- Disaster Recognition :cloud_tornado: : Automatically identify the type of disaster (e.g., fire, earthquake, flood) and its severity level.
- Department Contact Information :telephone_receiver: : Find contact information for the appropriate response departments, such as police, fire stations, medical facilities, and more.
With our system, you can ensure a swift and coordinated response to any emergency, potentially saving lives and minimizing damage. Don't hesitate to use the features provided to make informed decisions during critical situations.

# How we built it :wrench: 
We use Assembly AI to generate transcription from the call which identifies the speaker and gives labels too. We use our custom cohere model to detect the type of disaster by training it with some data. And made a DB with a lot of disaster management locations so one can measure distance easily. And used flask to build the application and integrate all of them.

# Challenges we ran into :thinking: 
While interacting with maps we felt a bit new so it took some time.
And trying to build a model that can classify disasters was hard because there is no dataset, we built our own.

# Accomplishments that we're proud of :tada: 
We managed to create an application that can help people who are in emergency and make those officers' lives easy and work better. Made our own AI models :robot:. Figured out how to use Assembly AI.

# What we learned :brain: 
Learned how Assembly AI works :nerd:. Learned how disaster management centers function :globe_with_meridians: .

# What's next for Emergency Response System :rocket: 
We are thinking of adding a function which will make calls to emergency services, family automatically whenever someone is stuck in an emergency.

Contributors:
Thanks to @Ashuradhipathi, @im45145v, my teammates in the Hash-it-out hackathon, who developed this project along with me.
Credits:
Special credits to the folks over here, https://devpost.com/software/draft-w86vkc, who created a very similar project before us.
