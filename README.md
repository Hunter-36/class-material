# Welcome to CIS 241 - System-level Programming and Utilities, Fall 2021

## About the Course

### Course Overview
This course should help acquaint you with:

* Navigating and using a Unix-based OS (primarily Linux)
* Remote access and file transfer for Unix systems
* Linux utilities and scripting
* Git/Github
* Programming with a system-level language (C) and memory management

### Helpful Links

* [Syllabus](syllabus.md)
* [Piazza](https://www.piazza.com/gvsu/fall2021/cis241/home) -- also [FAQ about Piazza](piazza-faq.md)
* [PrairieLearn](https://www.prairielearn.org/pl/course_instance/128857) - log-in
  using "Google" and use your GVSU gmail account
* [ClassTranscribe](https://classtranscribe.illinois.edu/offering/2eda65cf-d00f-4a0b-bb00-7bba2f88ccc6) -
  select "Google" sign-in and use your GVSU gmail account
* [GVSU VPN Instructions](https://www.gvsu.edu/it/downloading-installing-and-setting-up-pulse-secure-222.htm)

### Need Help?
If you have questions, please ask!  I'm here to help.  I welcome students
to drop by office hours, either virtual or in-person,
to work on their projects and listen to questions others might have (or chat
about other CS topics, grad school, etc.)

### COVID
While the goal for this semester is to be as normal as possilbe,
with COVID there will still likely be
surprises and we will need to be flexible to accommodate changes.

I recognize the difficulties some of you may face.
My goal is to make this semester as effective and as smooth
as possible.  Please reach out to me early and keep me informed
of any issues that arise.

### Course Schedule
This table outlines the entire course schedule.  Lecture notes are
posted for each topic.  Lecture videos, although not direct recordings
of this semester's live lectures, cover the same topics and are beneficial
if you are sick or do not feel comfortable attending in person.
Minilab links will be added prior to the start of class.  The dates in this
schedule are tentative and subject to change.

| Week | Date          | Topics | Activities | TODOs |
| ---- | ------------- | ------ | ---------- | --------- |
|  01  | 08/30 - 09/03 | introduction <br> ssh [video](https://classtranscribe.illinois.edu/video?id=a8f032d1-09c8-4740-9e61-0be5611a6654) [slides](lec-notes/lec01-intro-ssh.pdf) <br> navigating linux [video](https://classtranscribe.illinois.edu/video?id=74811691-a0a1-4b97-8650-d7a381f958e1) [slides](lec-notes/lec02-linux-filesystem-basics.pdf)  <br> viewing files [video](https://classtranscribe.illinois.edu/video?id=47b56232-1d5c-4c8a-8f78-3982a03b1dd1) [slides](lec-notes/lec03-viewing-files.pdf) <br> file transfer [video](https://classtranscribe.illinois.edu/video?id=f82ca560-7708-4204-8687-a6e41b563043) [slides](lec-notes/lec04-scp-rsync.pdf)  | [Friday: minilab 0](minilabs/minilab00.md) <br> [Friday: minilab 1](minilabs/minilab01.md) | Create a [Piazza account](https://www.piazza.com/gvsu/fall2021/cis241/home) <br> Create a [github](https://github.com/) account (if you do not already have one) <br> [Course Survey due Friday 09/03](https://forms.gle/EBVfg2segQKZJfwQ7) <br> Windows Users Only:  [Enable the Linux Subsystem](wsl-guide.md) by Fri 09/03 |
|  02  | 09/06 - 09/10 | No Class 09/06 (Labor Day) <br>sshkeys [video](https://classtranscribe.illinois.edu/video?id=8c240760-bbbf-4cf2-be22-a5413b148f2a) [slides](lec-notes/lec05-sshkeys-sshaliases.pdf) <br> script/history [video](https://classtranscribe.illinois.edu/video?id=068ca65e-35fe-446f-aae5-a9124421ff30) [slides](lec-notes/lec06-history.pdf) <br> IO redirection [video](https://classtranscribe.illinois.edu/video?id=11d4ce0d-ed37-4655-94d5-8033c411d42f) [slides](lec-notes/lec07-redirection.pdf) <br> linux utilities [video](https://classtranscribe.illinois.edu/video?id=98ba84fd-7258-451a-891e-d74759905aae) [slides](lec-notes/lec08-cut-tr-wc.pdf) | [Wednesday: minilab 2](minilabs/minilab02.md) <br> [Friday: minilab3](minilabs/minilab03.md) | - |
|  03  | 09/13 - 09/17 | compression [video](https://classtranscribe.illinois.edu/video?id=88ceb63c-5d19-4145-93ca-06d7fa6506b6) [slides](lec-notes/lec09-compression.pdf) [files](misc-files/week03/compression) <br> diff/piping [video](https://classtranscribe.illinois.edu/video?id=b0b2129a-67e4-41d8-8182-c2165c75bc84) [slides](lec-notes/lec10-diff-piping.pdf) [files](misc-files/week03/diff) <br> vim [video](https://classtranscribe.illinois.edu/video?id=ea139982-7d96-4f05-a029-e93544173e57) [slides](lec-notes/lec18-vim.pdf) [files](misc-files/week03/vim) <br> grep [video](https://classtranscribe.illinois.edu/video?id=9d4b753d-0aa1-4b50-b1e9-2c8403ae12a6) [slides](lec-notes/lec11-grep-wildcards.pdf) [files](misc-files/week03/grep) | [Friday: minilab4](minilabs/minilab04.md) | [Project 1 Assigned](https://www.prairielearn.org/pl/course_instance/128857/assessment/2313923) <br> [Sign-up for Quiz Time Slot](https://docs.google.com/spreadsheets/d/13qnN-bzuNcj_nUj6hIWbejbFWxyvynXfqLxFUAc-vrM/edit?usp=sharing) <br> [Quiz Review Guide](misc-files/quiz-review.md) |
|  04  | 09/20 - 09/24 | git overview [video](https://classtranscribe.illinois.edu/video?id=881e9710-2f41-4461-972c-ec0f32ae59b3) [slides](lec-notes/lec12-git-overview.pdf) <br> git intro [video](https://classtranscribe.illinois.edu/video?id=c590ff8f-7a26-4743-9add-df5a72a8a4c9) [slides](lec-notes/lec13-git-intro.pdf) <br> git branching [video](https://classtranscribe.illinois.edu/video?id=e48a0506-df26-469a-8dbb-c077bffa5cdb) [slides](lec-notes/lec14-git-branching.pdf) <br> git merging [video](https://classtranscribe.illinois.edu/video?id=55eb47cc-7aae-41cb-8207-1fa07d4c2e70) [slides](lec-notes/lec16-git-merging.pdf) <br> git remotes [video](https://classtranscribe.illinois.edu/video?id=a69c17e1-7f00-4d8c-bb54-c986ebeddef3) [slides](lec-notes/lec15-git-remotes.pdf)  | [Wednesday: minilab 5](minilabs/minilab05.md) | Command Line Quiz (M-W) |
|  05  | 09/27 - 10/01 | git other [video](https://classtranscribe.illinois.edu/video?id=ebc71085-1ca2-4b9c-baa9-f1a3dbd4bc43) [slides](lec-notes/lec17-git-other.pdf) <br> permissions/path [video](https://classtranscribe.illinois.edu/video?id=c7ffd473-eb6c-4035-af25-4b96f9fdafbc) [slides](lec-notes/lec19-permissions-path.pdf) <br> installing from source [video](https://classtranscribe.illinois.edu/video?id=79af3bd0-16d0-4928-a7b6-3e0c91b05ab7) [slides](lec-notes/lec20-installing-from-source.pdf) <br> processes [video](https://classtranscribe.illinois.edu/video?id=238ec2bd-c01d-410f-9f93-0cd121c4ca74) [slides](lec-notes/lec21-processes.pdf) <br> Bash scripting: <br> basics [video](https://classtranscribe.illinois.edu/video?id=91542cf6-4f84-41d4-9108-e4aee7e7c814) [slides](lec-notes/lec22-bash-scripting-basics.pdf) [script](misc-files/week06/bash-scripts/basic.sh)  <br> arguments [video](https://classtranscribe.illinois.edu/video?id=647eda3e-b36a-46ff-ab83-5343b9705fba) [slides](lec-notes/lec23-bash-scripting-arguments.pdf) [script](misc-files/week06/bash-scripts/arguments.sh) | [Monday: minilab6](minilabs/minilab06.md) <br> [Friday: minilab7](minilabs/minilab07.md) | Project 1 Due Thursday, September 30 @ 11:59pm|
|  06  | 10/04 - 10/08 | Bash Scripting <br> variables [video](https://classtranscribe.illinois.edu/video?id=36835a8e-ac0f-40c7-a56a-c6d075fff562) [slides](lec-notes/lec24-bash-scripting-variables-arithmetic.pdf) [script](misc-files/week06/bash-scripts/variables.sh) <br> conditionals [video](https://classtranscribe.illinois.edu/video?id=10e2208d-771e-416f-83b6-1f58cc476560) [slides](lec-notes/lec25-bash-scripting-conditionals.pdf) [script](misc-files/week06/bash-scripts/conditionals.sh) <br> loops [video](https://classtranscribe.illinois.edu/video?id=1a488428-4ac1-417e-9378-6790c565b6bd) [slides](lec-notes/lec26-bash-scripting-loops.pdf) [script](misc-files/week06/bash-scripts/loops.sh) <br> arrays [video](https://classtranscribe.illinois.edu/video?id=dabb2916-5171-44d0-bc54-17cbcf630e06) [slides](lec-notes/lec27-bash-scripting-arrays.pdf) [script](misc-files/week06/bash-scripts/arrays.sh) <br> functions [video](https://classtranscribe.illinois.edu/video?id=1a1227fd-394b-41a8-a743-065af7571de5) [slides](lec-notes/lec28-bash-scripting-functions.pdf) [script](misc-files/week06/bash-scripts/functions.sh) | [Monday: minilab08](minilabs/minilab08.md) <br> [Friday: minilab09](minilabs/minilab09.md) | |
|  07  | 10/11 - 10/15 | regex basics [video](https://classtranscribe.illinois.edu/video?id=d3cb9c39-fe39-427c-a626-afdc54a903b5) [slides](lec-notes/lec29-regex.pdf) <br> regex and grep [video](https://classtranscribe.illinois.edu/video?id=fd635645-8ee4-412b-89eb-bbd09f5dd74f) [slides](lec-notes/lec30-regex-grep.pdf) <br> sed [video](https://classtranscribe.illinois.edu/video?id=54f05088-5adb-4f8f-baba-4aa65b59e624) [slides](lec-notes/lec31-sed.pdf) <br> Files: [random files](misc-files/week07) [books](misc-files/written-texts) <br> [Minilab11 Solution Video](https://classtranscribe.illinois.edu/video?id=3a82ae15-a48c-4730-9e48-7fd24a0abae9)  | [Monday: minilab10](minilabs/minilab10.md) <br> [Wednesday: minilab11](minilabs/minilab11.md)  | [Project 2 Assigned](https://www.prairielearn.org/pl/course_instance/128857/assessment/2314432) |
|  08  | 10/18 - 10/22 | gawk basics [video](https://classtranscribe.illinois.edu/video?id=4fd70483-5289-40d7-9489-1f2bd69e0f0d) [slides](lec-notes/lec32-gawk-basics.pdf) [script](misc-files/week08/script-basics.awk) <br> gawk adv [video](https://classtranscribe.illinois.edu/video?id=684266bc-7be4-400e-8fea-1a194672aa4a) [slides](lec-notes/lec33-gawk-advanced.pdf) [script](misc-files/week08/script-advanced.awk) <br> C intro [video](https://classtranscribe.illinois.edu/video?id=711bfa10-2296-4571-96e3-7441a89de8ec) [slides](lec-notes/lec34-c-intro.pdf) <br> C compiling [video](https://classtranscribe.illinois.edu/video?id=7b7645ec-3fa3-4c8c-bf04-0dcd79536df5) [slides](lec-notes/lec35-c-compiling.pdf) <br>  C printing [video](https://classtranscribe.illinois.edu/video?id=36343308-b4f6-4500-bf0d-79a841141d71) [slides](lec-notes/lec36-c-types-print.pdf) [script](misc-files/week09/types-printing.c) | [Monday: minilab12](minilabs/minilab12.md) <br> [Friday: minilab13](minilabs/minilab13.md) | PL Practice Quiz (see minilab 13) |
|  09  | 10/25 - 10/29 | No Class 10/25 (Fall Break) <br> C basics [video](https://classtranscribe.illinois.edu/video?id=9aba1043-3a71-4df0-ac89-1fbf7b8edd92) [slides](lec-notes/lec37-c-operations-conditionals.pdf) [script](misc-files/week09/ops-cond.c) <br> C loops [video](https://classtranscribe.illinois.edu/video?id=6b1dff74-7750-46e6-9a68-7abb85d852d5) [slides](lec-notes/lec38-c-loops.pdf) [script](misc-files/week09/loops.c) <br> C pointers [video](TODO) [slides](lec-notes/lec39-c-pointers.pdf) [script](misc-files/week09/pointers-intro.c) | [Wednesday: minilab14](minilabs/minilab14.md)  | Project 2 Due Friday, October 29 @ 11:59pm |
|  10  | 11/01 - 11/05 | C stack vs heap [video](https://classtranscribe.illinois.edu/video?id=235f3ffb-55db-4f53-8f93-6af697dca51f) [slides](lec-notes/lec40-c-stack-heap.pdf) <br> C memory allocation [video](https://classtranscribe.illinois.edu/video?id=e259913b-6839-45ff-ae78-59ff03d24d17) [slides](lec-notes/lec41-allocating-memory.pdf) [script](misc-files/week10/memory-allocation.c) <br> C arrays & pointers [video](https://classtranscribe.illinois.edu/video?id=a2b15736-733b-48bd-870f-3b2c7110851b) [slides](lec-notes/lec42-pointers-arrays.pdf) [script](misc-files/week10/pointers-arrays.c)  | [Friday: minilab 15](minilabs/minilab15.md) | [Midterm Monday 11/01](https://www.prairielearn.org/pl/course_instance/128857/assessment/2314695) <br> [Midterm Study Guide](misc-files/midterm-recap.md) <br> Project 3 Released (tentative) |
|  11  | 11/08 - 11/12 | C input [video](https://classtranscribe.illinois.edu/video?id=fa3c3c7e-e8e3-44ff-b5fd-f706c2be7767) [slides](lec-notes/lec43-c-stdin.pdf) [script](misc-files/week11/reading-input.c) <br> C functions [video](https://classtranscribe.illinois.edu/video?id=839a1be9-5df7-43eb-aee5-6e0da84d5168) [slides](lec-notes/lec44-c-funcs.pdf) [script](misc-files/week11/functions.c) <br> switch [video](https://classtranscribe.illinois.edu/video?id=1608ce32-ff0b-4f6d-97ab-0cf9dca38294) [slides](lec-notes/lec45-c-switch.pdf) [script](misc-files/week11/switch.c) <br> header files [video](https://classtranscribe.illinois.edu/video?id=46004239-92ce-4754-9688-393ff2ef1ada) [slides](lec-notes/lec46-c-header-files.pdf) [files](misc-files/week11/headers) | |  |
|  12  | 11/15 - 11/19 | C structs [video](https://classtranscribe.illinois.edu/video?id=7b0e4ad7-69ed-44fe-b002-31ab37885284) [slides](lec-notes/lec47-c-structs.pdf) [script](misc-files/week12/structs.c) <br> 2d arrays - stack [video](https://classtranscribe.illinois.edu/video?id=69290b57-3414-457a-bc15-bca55f6f0426) [slides](lec-notes/lec48-2d-arrays-stack.pdf) [script](misc-files/week12/2d-arrays-stack.c) <br> 2d arrays - dynamic allocation [video](https://classtranscribe.illinois.edu/video?id=e623febd-addf-472a-82dd-7135e59d7d10) [slides](lec-notes/lec49-2d-arrays-dynamic-allocation.pdf) [script](misc-files/week12/2d-arrays-dynamic.c) <br> Recommended Reading [Chap 4 Understanding and Using C Pointers by Reese](https://www.oreilly.com/library/view/understanding-and-using/9781449344535/ch04.html) |  | Project 3 due (tentative) <br> Project 4 Released (tentative) |
|  13  | 11/22 - 11/26 | makefiles [video](https://classtranscribe.illinois.edu/video?id=030c294f-d86c-4c6b-a346-49c68e4d56ab) [slides](lec-notes/lec50-makefiles.pdf) [scripts](misc-files/week13/makefiles) <br> No Class 11/24 & 11/26 (Thanksgiving)|  |  |
|  14  | 11/29 - 12/03 | C string funcs [video](https://classtranscribe.illinois.edu/video?id=9247b107-deb0-40bb-a1ed-1311c918e621) [slides](lec-notes/lec51-stringfuncs.pdf) [script](misc-files/week14/strings.c) <br> C mem funcs [video](https://classtranscribe.illinois.edu/video?id=9b12e096-00b0-4c08-9cd4-e589eec98c74) [slides](lec-notes/lec52-memory-copy-funcs.pdf) [script](misc-files/week14/mem-funcs.c) <br> gdb/valgrind [video](https://classtranscribe.illinois.edu/video?id=a4821d5e-9f60-4245-89dd-27638245d6fc) [slides](lec-notes/lec53-debugging.pdf) <br> [original buggy script](misc-files/week14/debugging/orig-buggy.c)  | | |
|  15  | 12/06 - 12/10 | C arguments [video](https://classtranscribe.illinois.edu/video?id=4f46f2d0-a34d-4ceb-92fd-ec8943b29491) [slides](lec-notes/lec54-arguments.pdf) [script](misc-files/week15/arguments.c) <br> C enums/unions [video](https://classtranscribe.illinois.edu/video?id=91092008-6c2d-4907-9e6d-f252d054b99a) [slides](lec-notes/lec55-enums-unions.pdf) [script](misc-files/week15/enums-unions.c) <br> C fileio [video](https://classtranscribe.illinois.edu/video?id=7357532a-9e40-45e0-9d09-c818f562ce6b) [slides](lec-notes/lec56-fileio.pdf) [files](misc-files/week15/file-io) <br> C libraries/misc [video](https://classtranscribe.illinois.edu/video?id=85ab940c-dd41-44a7-98e3-c3067e5c5b0e) [slides](lec-notes/lec57-c-misc.pdf) | | Project 4 Due (tentative) |
|  16  | 12/13 - 12/17 | FINAL EXAM:  TBA |  |  |
