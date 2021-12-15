# ABOUT SAFE HAVEN PSEUDONYMIZATION

About how the West of Scotland Safe Haven in Glasgow pseudonymizes electronic health records prior to re-use for research.

## DEFINITIONS

Anonymization, "The process of removing all personal identifiers from a dataset, rendering it impossible to re-identify any individual from all or part of that dataset."

Pseudonymization, "The process of removing, replacing, or otherwise obfuscating data-points in order to disguise the likely identity of an individual, whilst still retaining the ability to link back to a real-world personal record."

Identifiable information, "Any data collection, data row, or data-point that can be used to establish, whole or in part, the real identity of any individual; for example, may include name, address, date of birth, or a unique identifier."

## PSEUDONYMIZATION: GENERAL METHODS

The re-identification risk posed by data elements is judged according to multiple factors: the size of the dataset, the environment it will be analysed in, the type of research. The greater the risk of re-identification, the more aggressive the pseudonymization the Safe Haven will apply.

Methods we use, from most aggressive to least, include:

1. Removal
2. Redaction
3. Obfuscation
4. Substitution
5. Retention

## GENERAL NOTE ON UIDs

An UID is a unique identifier used by an information system to identify a record, event, or patient.

The Safe Haven will normally remove all UIDs when prepping a dataset because they could be used to link back to the originating system, and hence infer an individual's identity.

UIDs are also not required for research purposes. As a convention, Safe Haven will therefore strip out all UIDs by removal prior to extraction for research.