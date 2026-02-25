# OmniDoc - Hack OHI/O 2024, 1st place
<p align="center">
  <img src="omnidoc_logo.png" />
</p>

omnidoc is a voice-to-voice ai agent that automates patient intake and helps structure the diagnosis of common illness symptoms before a patient ever sees a physician.

healthcare providers and hospital staff are often overwhelmed, spending significant time gathering basic symptom information, clarifying patient histories, and organizing notes. this administrative and intake burden reduces the time physicians can spend on actual clinical decision-making.

omnidoc addresses this by conducting a structured, real-time voice conversation with patients. it asks targeted follow-up questions, clarifies symptoms, and systematically collects relevant health information. the system guides patients through a dynamic diagnostic flow so that their responses are complete, organized, and clinically useful.

after the conversation, omnidoc generates a concise intake report that physicians can review inside a web application prior to the appointment. this provides clearer context, improves preparedness, and streamlines the diagnostic process.

the system leverages openai’s speech and language models for voice interaction and reasoning, and is supported by a django-based web application with a postgres database backend.
<p align="center">
  <img src="omnidoc_diagram.png" />
</p>
