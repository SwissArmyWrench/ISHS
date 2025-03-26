
# Interleaved Subject Header System

This system applies to a notebook containing entries about different subjects that are not necessarily perfectly separated and may be interleaved together.

## Terms

In this specification the following terms are used as described:

**SUBJECT**: A specific subject, project, or topic about which notes may be taken.

**ENTRY**: One individual entry about one and only one SUBJECT.

**SEGMENT**: a continuous block of consecutive ENTRIES concerning the same SUBJECT.

**HEADER**: A title block / header that contains data about the SUBJECT and SEGMENT.


## Rules

### Subjects

- Each SUBJECT is identified solely by its name or title.


### Entries

- Each ENTRY may only address one SUBJECT.

- Each ENTRY should be marked with a number and the date of entry.

- ENTRIES must be numbered consecutively.

- A new ENTRY should be started each day.

- If notes about multiple SUBJECTS are taken in one day, a new ENTRY and SEGMENT must be created.


### Segments

- SEGMENTS each begin with a HEADER, defined below

- SEGMENTS may only contain ENTRIES about one SUBJECT.

- SEGMENTS are numbered consecutively, regardless of subject.

- SEGMENTS may additionally carry a number for their position in a given SUBJECT. For example, the 2nd SEGMENT of a given SUBJECT would be labeled as "<Subject> 2" in the HEADER, even if it might be the 10th SEGMENT of the notebook.


### Headers

- The SUBJECT's name, and the number designating this SEGMENT within that SUBJECT's notes (such as Lamp Repair 2 to designate the 2nd SEGMENT of the SUBJECT)

- The range of ENTRIES contained in the segment, including the first and last. The first can be filled in upon creation of the SEGMENT but the last should be filled in upon creation of the following SEGMENT.

- The date range matching the ENTRIES mentioned above with start and end dates filled out in the same manner.

- The SEGMENT's number (out of all SEGMENTS created)

- The page numbers of the previous and next segments of this particular SUBJECT

- Optionally, if these notes are being transcribed, the date of transcription may be added when it has been completed for this SEGMENT.

- An example header is shown below. This means that that this segment is the 2nd segment of the "Lamp" project, as indicated under PROJECT. It contains ENTRIES 6 to 16, covering dates from 2-16 to 3-12. It is the third segment in total, the previous Lamp segment starts on page 1, and the following Lamp segments starts on page 10. Transcription for this segment was completed on 4-27.

| PROJECT | ENTRIES | DATES             | SEG# | PREV | NEXT | TRANSCRIBED |
|---------|---------|-------------------|------|------|------|-------------|
| Lamp 2  | 6 - 16  | 2/16/24 - 3/12/24 | 3    | 1    | 10   | 4/27/24     |

