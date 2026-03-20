This page is a running list of Open Source Operating Systems (Linux & *BSD distributions, etc.) and what their current status is regarding ID verification.

There are several locales which have laws (in various stages) which require Operating Systems themselves to perform some level of ID verification and reporting.

Passed OS-Level ID Verification Laws: [Brazil](https://x.com/lundukejournal/status/2033927808196481101), & [California](https://x.com/lundukejournal/status/2026783141298360692).

Proposed OS-Level ID Verification Laws: [Colorado](https://x.com/lundukejournal/status/2026331487499370988), [Illinois](https://x.com/lundukejournal/status/2031047619225493597), & [New York](https://x.com/lundukejournal/status/2029081398577922173?s=61).

### Operating Systems Not Implementing ID Verification

The developers or publishers of these open source Operating Systems have decided to not implement ID Verification, or are currently restricting access in regions with ID Verification laws.

| &nbsp; | Operating System | Notes |
| - | - | - |
| :no_entry: | **Omarchy Linux** | [Developer statement](https://x.com/lundukejournal/status/2029580164498108846) |
| :no_entry: | **Devuan Linux** | [Developer statement](https://x.com/lundukejournal/status/2034697759291310115) |
| :no_entry: | **FreeDOS** | [Developer statement](https://x.com/lundukejournal/status/2034770975309361583) |
| :no_entry: | **Artix Linux** | [Developer statement](https://x.com/lundukejournal/status/2034776326901555488) |
| :no_entry: | **DB48X** | Calculator firmware, [Developer statement](https://x.com/lundukejournal/status/2027358439991615715) |
| :no_entry: | **Arch Linux 32** | [Developer forbids usage in Brazil, California](https://x.com/lundukejournal/status/2033896030178029675) |
| :no_entry: | **Ageless Linux** | [Debian fork created to protest "AGE" Verification](https://x.com/lundukejournal/status/2032951803134837237) |
| :no_entry: | **Adenix GNU/Linux** | [States in their ToS, to not use the distro in "age-gated" states.](https://www.adenixgnulinux.org/tos) - [They also asked Debian to make it easier to remove said packages](https://lists.debian.org/debian-legal/2026/03/msg00022.html?ref=itsfoss.com) - [Thanks to issue #10](https://github.com/BryanLunduke/DoesItAgeVerify/issues/10)|

### Operating Systems Planning to Implement ID Verification

The developers or publishers of these Open Source Operating Systems have made plans and/or statements that they intend to comply with new ID Verification laws.  But, as yet, that ID Verfication functionality is not fully implemented.

| &nbsp; | Operating System | Notes |
| - | - | - |
| :building_construction: | **Ubuntu** | [Planning Discussion](https://lists.ubuntu.com/archives/ubuntu-devel/2026-March/043510.html), [Ubuntu VP Statement](https://x.com/lundukejournal/status/2029198322309681311) |
| :building_construction: | **Pop!_OS** | [System76 Statement opposing, but planning to implement](https://blog.system76.com/post/system76-on-age-verification) |
| :building_construction: | **elementary OS** | [Founder Statement planning to implement](https://mastodon.social/@danirabbit@mastodon.online/116250766314705297) |
| :building_construction: | **Midnight BSD** | [License temporarily forbids usage in Brazil, California](https://github.com/MidnightBSD/src?tab=License-1-ov-file), [until implementation finished](https://x.com/midnightbsd/status/2030992394703732872) |

### Operating Systems Which Have Already Implemented ID Verification

As of the most recent update to this document, no known Open Source Operating Systems have fully complied with legal ID Verification requirements for any jurisdiction.

### Known Software/OS Components that plan on implementing it (Including Software that calls the "age" API)
| &nbsp; | Software | Notes |
| - | - | - |
| :building_construction: | **systemd** | [GitHub Pull Request to implement it](https://github.com/systemd/systemd/pull/40954)  - If this goes through, most Linux distros would have it by default!|
