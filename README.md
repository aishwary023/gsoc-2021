# GSoC '21 @ Oppia
![oppia_gsoc](https://user-images.githubusercontent.com/26626415/131044965-a73c2df3-cdc7-4242-9465-b30b572c2a05.jpeg)

## Oppia
Oppia is platform which provides a novel and engaging approach to online learning for underprivileged children around the world. Oppia is specially designed to meet the unique needs of the under-resourced children.

## About the project
Oppia uses AngularJs/Angular 2+ for its frontend and has a massive codebase. It is crucial to test this code in order to catch any bug before it reaches to production. The aim of my GSoC project was to increase the code coverage by writing Frontend Unit Tests for directives, components, and services. Since the number of lines of code was a lot, the files were divided among 3 students. I was assigned **3207** lines to cover.

## Before GSoC
The code coverage was as follows before the begining of GSoC:
![image](https://user-images.githubusercontent.com/26626415/130315810-8d782dff-baa1-47ec-aba2-ddf5f59881f9.png)

## Before Milestone 1
Before milestone 1 began, I created 2 PRs which were extensively reviewd by [@sealip](https://github.com/seanlip), [@kevintab95](https://github.com/kevintab95), and [@nithusha21](https://github.com/nithusha21). You can see the 2 practice PRs and the extensive code review done by the mentors here:

Sr No. | PR                                                 | Status
-------|----------------------------------------------------|-------------
1 | [oppia/oppia#12936](https://github.com/oppia/oppia/pull/12936)| Merged ✅
2 | [oppia/oppia#12946](https://github.com/oppia/oppia/pull/12946)| Merged ✅

Based on the review recieved on these PRs, we created a section in the wiki page adding [📝 Guidelines to write robust tests](https://github.com/oppia/oppia/wiki/Frontend-unit-tests-guide#guidelines-to-write-robust-tests).

## Milestone 1
I covered **1785** line during milestone 1. Following PRs were created during Milestone 1:

Sr No. | PR                                                 | Status
-------|----------------------------------------------------|-------------
1|[oppia/oppia#13069](https://github.com/oppia/oppia/pull/13069)| Merged ✅
2|[oppia/oppia#13102](https://github.com/oppia/oppia/pull/13102)| Merged ✅
3|[oppia/oppia#13217](https://github.com/oppia/oppia/pull/13217)| Merged ✅
4|[oppia/oppia#13154](https://github.com/oppia/oppia/pull/13154)| Merged ✅
5|[oppia/oppia#13110](https://github.com/oppia/oppia/pull/13110)| Merged ✅
6|[oppia/oppia#13138](https://github.com/oppia/oppia/pull/13138)| Merged ✅
7|[oppia/oppia#13126](https://github.com/oppia/oppia/pull/13126)| Merged ✅
8|[oppia/oppia#13176](https://github.com/oppia/oppia/pull/13176)| Merged ✅
9|[oppia/oppia#13217](https://github.com/oppia/oppia/pull/13217)| Merged ✅
10|[oppia/oppia#13217](https://github.com/oppia/oppia/pull/13217)| Merged ✅
11|[oppia/oppia#13287](https://github.com/oppia/oppia/pull/13287)| Merged ✅
12|[oppia/oppia#13322](https://github.com/oppia/oppia/pull/13322)| Merged ✅
13|[oppia/oppia#13334](https://github.com/oppia/oppia/pull/13334)| Merged ✅

## Milestone 2
Covered **1216** during Milestone 2.

Sr No. | PR                                                 | Status
-------|----------------------------------------------------|-------------
1|[oppia/oppia#13418](https://github.com/oppia/oppia/pull/13069)| Merged ✅
2|[oppia/oppia#13442](https://github.com/oppia/oppia/pull/13102)| Merged ✅
3|[oppia/oppia#13479](https://github.com/oppia/oppia/pull/13217)| Merged ✅
4|[oppia/oppia#13554](https://github.com/oppia/oppia/pull/13154)| Merged ✅
5|[oppia/oppia#13587](https://github.com/oppia/oppia/pull/13110)| Merged ✅
6|[oppia/oppia#13606](https://github.com/oppia/oppia/pull/13138)| Merged ✅
7|[oppia/oppia#13673](https://github.com/oppia/oppia/pull/13126)| Merged ✅
8|[oppia/oppia#13685](https://github.com/oppia/oppia/pull/13176)| Merged ✅
9|[oppia/oppia#13366](https://github.com/oppia/oppia/pull/13217)| Merged ✅

## Work Completed
- ✅ Created 24 PRs, covering **3001**/3207 lines
- 📝 Added guidelines to write robust unit tests in the wiki
- 🔨 Fixed flakes as they were discovered during the course of GSoC
- 🧐 Reviewed fellow GSoCers pull requests

## After GSoC
The code coverage was as follows after GSoC:
![image](https://user-images.githubusercontent.com/26626415/130315540-a94d4209-b2a0-4737-9bcb-2b4d0a1d799d.png)
