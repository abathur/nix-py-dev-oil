# nix-py-dev-oil

This repo contains a Nix package for an *unofficial* Python module/package of another project that is not already packaged.

Feel free to use this if you: know what it is, know you want to use it, and accept the following tradeoffs:

1. This is the primary dependency of https://github.com/abathur/resholve. I'm extracting this into its own repo for workflow reasons, but still intend to manage/maintain it as a core dependency. Implications:
   - updates will probably be intermittent and dictated by resholve's needs/timeline
   - I may stop updating if upstream ever makes an irreconcilable break with what resholve needs
   - open to bugfixes and performance improvements, but I'll need convincing for anything else
2. This is *unofficial* package of pre-1.0 code that upstream does not publish as a public API. Implications:
   - Be prepared to learn by self-study (from resholve, and upstream's source).
   - Be prepared to track upstream API changes. Breaks are likely, and you'll have to sift through upstream commits to understand them.
   - Be prepared to carry patches for any changes you need to code upstream. (Upstream is receptive to some, especially fixes--but assuming you'll have to carry the patch will encourage easier-to-maintain changes.)
3. For resholve's success/stability, I need a good working relationship with the upstream project. I'll pull the plug on this package if it starts causing them trouble.
   - Please open issues/discussion _here_ if you have trouble with or questions about this package or using upstream's code. Actual behavior/parse problems should be fine to open upstream--but if you have any doubt, open here first. I'll do my best to answer/triage to minimize the support burden this creates upstream.
   - Build your own positive relationship upstream. Be generous/polite. Don't demand anything (i.e. docs, help, changes). Look for ways to invest time/effort in its success (can be as simple as contributing feedback on open questions and reporting interesting test/edge cases).
