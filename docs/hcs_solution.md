# HCS Solution

**HCS** is an **_integration pipeline or integration platform_** depending on the use case of the other parties. HCS at the core view various records as _a sequence of real life events_ and corresponding action to the events are triggered or requested by HCS.

**HCS** is built on the idea that health records can be classified as a `Read only Append Log (ROAL)`. What `Read only Append Log` means is that data is `immutable`, `non-deletable` but can only be `added` to. 

Another example is an accounting ledger, it's immutable, non-deletable and append to only, Any error can only be corrected by a corresponding entry, you can delete or erase an entry and you can only add to below the ledger. An accurate ledger is order by the time of entry on it's side.

This same ideas fundamentally applies to health care information and records.

## Core Idea's.
These are fundamental ideas that pillar's HCS and how they relate to the solution effectively.

### A Unique Healthcare Identity.
**HCS** platform provides every member a unique a healthcare identity, similar to the hospital card number provided to clients to identify and retrieve the card containg the client case files and medical histories as it progresses. The unique healthcare identity, will remove the need for different client card across institutions and static records that are often requested again increasing the speed of health care delivery in certain cases. A client can working into any health institution with their phoneNo or identity for continutiy of care history.

### Case Files.
Health organizations are creating a case file on the health identity, each organizations can only view case files particular to their own organization except in cases of referral in which the case file is sent to another organization. A `case file` contains all the records of care given from consultation, prescription, labouratory tests, results, child birth, ward admission and ward discharge which are regarded as `case records`.

In the simplest form, A case File is a folder containing case records, while the identity is the folder for all case file.

`Identity` (Singular) -> `Case File` (mutiple) -> `Case Record` (multiple).

### Case Records.
Case records are entries inside a case file and case records are of various types. A case record entry can create a trigger in some cases. I.e Child Birth can send information to *NIMC* and health parastals for national birth certificate, which can be printed out the same day. A patient referral will create a notification trigger to the recieving parastal for the case before arrival and evaluation. Confirmed labouratory test will create a trigger to alert the *CDC* in realtime to monitor possible pandemics, Case File Closed will create a trigger for any HMO for coverage automatically.

### Institutions.
Institutions are any health organizations offering care in one way or the other. Instituitons are classified into Primary, Secondary and Tertiary ordinary, but the fourth classification is `Aggregators`. The aggregators are EMR or various EHR's creating non aggregrator instutions like hospitals, clinic, pharamacies e.t.c. The only difference between Aggregators and other Institutions is that they can create other classes on HCS, providing some sort of service.