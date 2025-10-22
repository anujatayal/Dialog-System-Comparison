## Conversational Assistants to support Heart Failure Patients: Comparing a Neurosymbolic Architecture with GPT

<!-- Authors: Anuja Tayal, Barbara Di Eugenio, Devika Salunke, Andrew D. Boyd, Carolyn A Dickens, Eulalia P Abril, Olga Garcia-Bedoya, Paula G Allen-Meares
-->

Conversational assistants are becoming more and more popular, including in healthcare, partly because of the availability and capabilities of Large Language Models. There is a need for controlled, probing evaluations with real stakeholders which can highlight advantages and disadvantages of more traditional architectures and those based on generative AI. We present a within-group user study to compare two versions of a conversational assistant that allows heart failure patients to ask about the salt content in food. One version of the system was developed in-house with a neurosymbolic architecture, and one is based on GPT.

The study compares two dialog systems—an in-house Neuro-Symbolic System (HFFood-NS) with a GPT-based system (HFFood-GPT)—using a within-subject design. 
We conduct intrinsic (task performance)  and extrinsic analyses using pre- and post-interaction surveys to evaluate the 2 systems with African-American patients while hospitalized. We assessed participants’ health literacy and digital literacy using self-reported measures to better
understand their abilities to access and process health information.

At the end of the user study, a dataset of approximately 200 conversations was collected (20 patients × 5 food items × 2 models).


# Conversational Dataset
(final-dataset-deidentifed file)

hffood-ns-final – representing our in-house system. Since no de-identification is involved, a de-identified sheet is not applicable.

hffood-gpt-deidentified - deidentified version of the GPT-based system

Each sheet contains the following columns: file name, patient, and conversation. The conversations are structured as alternating turns between the user and the system.

The dataset includes interactions from 20 patients, labeled from p1 to p23 (note: some IDs may be skipped). Each patient asked up to 5 food-related questions, so the food ID ranges from 1 to 5. The file name format follows the structure: patientID-foodID-[correct].

Every row has a corresponding 'correct' version where any Speech-to-text (STT) errors have been corrected. STT errors occurred only in user utterances. For rows without STT errors, a duplicate ‘correct’ version has been added to maintain consistency across the dataset.
