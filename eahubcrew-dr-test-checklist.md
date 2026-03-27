# Eagle Hub Crew Disaster Recovery Test

__Organizer__: Patrick Faulkner

__Date__: 3/31/2026

## Shared Links

- **Splunk:** [link](https://eaglewatch.aa.com/en-US/app/eahubcrew_developers/search)
- **Dynatrace:** [link](https://kyy56528.apps.dynatrace.com/ui/apps/dynatrace.classic.synthetic/#monitors;gtf=-2h;gf=-4065568379935440957)

## Status Key

| Symbol | Meaning |
|--------|-------------|
| ✅ | Complete/Ready |
| 🟡 | In Progress |
| 🔷 | Not Started |
| 🔴 | Not Ready |

## Progress

| Category | Complete | Total | Status |
|----------|----------|-------|--------|
| Pipeline | 7 | 7 | ✅ |
| Dynatrace | 7 | 7 | ✅ |
| Repository | 7 | 7 | ✅ |
| Splunk | 7 | 7 | ✅ |
| **Overall** | **28** | **28** | **✅** |

## Dashboard

| Application | Pipeline | Dynatrace | Repository | Splunk | DR Ready? |
|-------------|----------|-----------|------------|--------|-----------|
| Crew Hub to Rainmaker | ✅ | ✅ | ✅ | ✅ | ✅ |
| Employee Central to Rainmaker | ✅ | ✅ | ✅ | ✅ | ✅ |
| Rainmaker Reconciliation | ✅ | ✅ | ✅ | ✅ | ✅ |
| Eagle Hub to MINT (ENY) | ✅ | ✅ | ✅ | ✅ | ✅ |
| Eagle Hub to MINT (PDT) | ✅ | ✅ | ✅ | ✅ | ✅ |
| Eagle Hub to MINT (PSA) | ✅ | ✅ | ✅ | ✅ | ✅ |
| LMS to MINT | ✅ | ✅ | ✅ | ✅ | ✅ |

## Applications

### Crew Hub to Rainmaker

**Ready for DR?:** ✅

**Primary Resource:** rgn-p-zeaus-rainmaker-crew-fa

**DR Resource:** rgn-p-zweus-rainmaker-crew-fa

**Links:**
- **Repository:** [link](https://dev.azure.com/AmericanAirlines/Regional_Enterprise_Programs/_git/EAHubCrew-CrewHubToRainmaker)
- **Pipeline:** [link](https://dev.azure.com/AmericanAirlines/Regional_Enterprise_Programs/_release?view=all&_a=releases&definitionId=298)
- **Dynatrace Synthetic (Primary):** [link](https://kyy56528.apps.dynatrace.com/ui/apps/dynatrace.classic.synthetic/ui/http-monitor/HTTP_CHECK-ADE929288939DA93?gtf=-2h&gf=-4065568379935440957)
- **Dynatrace Synthetic (DR):** [link](https://kyy56528.apps.dynatrace.com/ui/apps/dynatrace.classic.synthetic/ui/http-monitor/HTTP_CHECK-1AA44F23CD48B3EE?gtf=-2h&gf=-4065568379935440957)

|Pipeline Ready?|Dynatrace Ready?|Repository Ready?|Splunk Ready?|
|----|----|----|----|
|✅|✅|✅|✅|

**Remarks:**

---

### Employee Central to Rainmaker

**Ready for DR?:** ✅

**Primary Resource:** rgn-p-zeaus-rainmaker-sqlfile-fa

**DR Resource:** rgn-p-zweus-rainmaker-sqlfile-fa

**Links:**
- **Repository:** [link](https://dev.azure.com/AmericanAirlines/Regional_Enterprise_Programs/_git/EAHubCrew-EcToRainmaker)
- **Pipeline:** [link](https://dev.azure.com/AmericanAirlines/Regional_Enterprise_Programs/_release?view=all&_a=releases&definitionId=289)
- **Dynatrace Synthetic (Primary):** [link](https://kyy56528.apps.dynatrace.com/ui/apps/dynatrace.classic.synthetic/ui/http-monitor/HTTP_CHECK-41FB1E645D22C783?gtf=-2h&gf=-4065568379935440957)
- **Dynatrace Synthetic (DR):** [link](https://kyy56528.apps.dynatrace.com/ui/apps/dynatrace.classic.synthetic/ui/http-monitor/HTTP_CHECK-0B18D77BA2ED9B50?gtf=-2h&gf=-4065568379935440957)

|Pipeline Ready?|Dynatrace Ready?|Repository Ready?|Splunk Ready?|
|----|----|----|----|
|✅|✅|✅|✅|

**Remarks:**

---

### Rainmaker Reconciliation

**Ready for DR?:** ✅

**Primary Resource:** rgn-p-zeaus-rainmaker-recon-fa

**DR Resource:** rgn-p-zweus-rainmaker-recon-fa

**Links:**
- **Repository:** [link](https://dev.azure.com/AmericanAirlines/Regional_Enterprise_Programs/_git/EaHubCrew-RainmakerReconciliation)
- **Pipeline:** [link](https://dev.azure.com/AmericanAirlines/Regional_Enterprise_Programs/_release?view=all&_a=releases&definitionId=425)
- **Dynatrace Synthetic (Primary):** [link](https://kyy56528.apps.dynatrace.com/ui/apps/dynatrace.classic.synthetic/ui/http-monitor/HTTP_CHECK-0F5090BB456C375B?gtf=-2h&gf=-4065568379935440957)
- **Dynatrace Synthetic (DR):** [link](https://kyy56528.apps.dynatrace.com/ui/apps/dynatrace.classic.synthetic/ui/http-monitor/HTTP_CHECK-9138369E365163E5?gtf=-2h&gf=-4065568379935440957)

|Pipeline Ready?|Dynatrace Ready?|Repository Ready?|Splunk Ready?|
|----|----|----|----|
|✅|✅|✅|✅|

**Remarks:**

---

### Eagle Hub to MINT (ENY)

**Ready for DR?:** ✅

**Primary Resource:** rgn-p-zeaus-EagleHubToMint-ENY-fa

**DR Resource:** rgn-p-zweus-EagleHubToMint-ENY-fa

**Links:**
- **Repository:** [link](https://dev.azure.com/AmericanAirlines/Regional_Enterprise_Programs/_git/EAHubCrew-EagleHubToMINT)
- **Pipeline:** [link](https://dev.azure.com/AmericanAirlines/Regional_Enterprise_Programs/_release?view=all&_a=releases&definitionId=395)
- **Dynatrace Synthetic (Primary):** [link](https://kyy56528.apps.dynatrace.com/ui/apps/dynatrace.classic.synthetic/ui/http-monitor/HTTP_CHECK-0A81505E88FD9874?gtf=-2h&gf=-4065568379935440957)
- **Dynatrace Synthetic (DR):** [link](https://kyy56528.apps.dynatrace.com/ui/apps/dynatrace.classic.synthetic/ui/http-monitor/HTTP_CHECK-7875066C12537DB1?gtf=-2h&gf=-4065568379935440957)

|Pipeline Ready?|Dynatrace Ready?|Repository Ready?|Splunk Ready?|
|----|----|----|----|
|✅|✅|✅|✅|

**Remarks:**

---

### Eagle Hub to MINT (PDT)

**Ready for DR?:** ✅

**Primary Resource:** rgn-p-zeaus-EagleHubToMint-PDT-fa

**DR Resource:** rgn-p-zweus-EagleHubToMint-PDT-fa

**Links:**
- **Repository:** [link](https://dev.azure.com/AmericanAirlines/Regional_Enterprise_Programs/_git/EAHubCrew-EagleHubToMINT)
- **Pipeline:** [link](https://dev.azure.com/AmericanAirlines/Regional_Enterprise_Programs/_release?view=all&_a=releases&definitionId=393)
- **Dynatrace Synthetic (Primary):** [link](https://kyy56528.apps.dynatrace.com/ui/apps/dynatrace.classic.synthetic/ui/http-monitor/HTTP_CHECK-7CD09C79DE5DC778?gtf=-2h&gf=-4065568379935440957)
- **Dynatrace Synthetic (DR):** [link](https://kyy56528.apps.dynatrace.com/ui/apps/dynatrace.classic.synthetic/ui/http-monitor/HTTP_CHECK-36262E7403EDEEE2?gtf=-2h&gf=-4065568379935440957)

|Pipeline Ready?|Dynatrace Ready?|Repository Ready?|Splunk Ready?|
|----|----|----|----|
|✅|✅|✅|✅|

**Remarks:**

---

### Eagle Hub to MINT (PSA)

**Ready for DR?:** ✅

**Primary Resource:** rgn-p-zeaus-EagleHubToMint-PSA-fa

**DR Resource:** rgn-p-zweus-EagleHubToMint-PSA-fa

**Links:**
- **Repository:** [link](https://dev.azure.com/AmericanAirlines/Regional_Enterprise_Programs/_git/EAHubCrew-EagleHubToMINT)
- **Pipeline:** [link](https://dev.azure.com/AmericanAirlines/Regional_Enterprise_Programs/_release?view=all&_a=releases&definitionId=469)
- **Dynatrace Synthetic (Primary):** [link](https://kyy56528.apps.dynatrace.com/ui/apps/dynatrace.classic.synthetic/ui/http-monitor/HTTP_CHECK-5EF0FF35D36318A0?gtf=-2h&gf=-4065568379935440957)
- **Dynatrace Synthetic (DR):** [link](https://kyy56528.apps.dynatrace.com/ui/apps/dynatrace.classic.synthetic/ui/http-monitor/HTTP_CHECK-E8B89EFDEDF49EF1?gtf=-2h&gf=-4065568379935440957)

|Pipeline Ready?|Dynatrace Ready?|Repository Ready?|Splunk Ready?|
|----|----|----|----|
|✅|✅|✅|✅|

**Remarks:**

---

### LMS to MINT

**Ready for DR?:** ✅

**Primary Resource:** rgn-p-zeaus-lmstomint-fa

**DR Resource:** rgn-p-zeaus-lmstomint-fa

**Links:**
- **Repository:** [link](https://dev.azure.com/AmericanAirlines/Regional_Enterprise_Programs/_git/EaHubCrew-LMSToMINT_FA)
- **Pipeline:** [link](https://dev.azure.com/AmericanAirlines/Regional_Enterprise_Programs/_release?view=all&_a=releases&definitionId=365)
- **Dynatrace Synthetic (Primary):** [link](https://kyy56528.apps.dynatrace.com/ui/apps/dynatrace.classic.synthetic/ui/http-monitor/HTTP_CHECK-B88E331DBE1F7931?gtf=-2h&gf=-4065568379935440957)
- **Dynatrace Synthetic (DR):** [link]()

|Pipeline Ready?|Dynatrace Ready?|Repository Ready?|Splunk Ready?|
|----|----|----|----|
|✅|✅|✅|✅|

**Remarks:**

Identify/create DR EMFT job.

---

## Findings

### LMS to MINT — No DR EMFT Job

The LMS to MINT integration relies on an EMFT job that drops a file into the Azure East Blob Storage Account, which triggers the application. There is currently no DR EMFT job configured to target the Azure West Blob Storage Account. If a DR EMFT job cannot be created before the test date, we will be unable to run LMS to MINT out of Azure West for the allotted one-week DR period.
