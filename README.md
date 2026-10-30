I make broadcast video, 3D and AR for climbing competitions at [OnlineObservation](https://onlineobservation.com), as an AI trainer, I also review and correct AI output. I don't like AI slop, in the word or in the look of it, so I'd rather ship something plain and human than something polished and generic. This page tries to follow that.

クライミング大会の映像・3D・ARを作る [OnlineObservation](https://onlineobservation.com) の代表です。AIトレーナーとして、AIの出力を見て直す仕事もしています。AIスロップは言葉としても見た目としても好きではないので、この文章も飾らずに書いています。

## What I can evaluate

**1. 3D and video, in a live broadcast setting.**
I build 3D and video for climbing broadcasts, where a wrong frame or a warped model goes on air. I look at what AI produces in these areas (photogrammetry meshes with hand-filled gaps, segmentation boundaries, color-space tags in generated video, camera pose solves, texture resolution), find what is wrong, say why, and fix it. Work and notes: [3d-video-ai-review](https://github.com/masato221/3d-video-ai-review)
What the broadcast work looks like, as it goes to TV directors: [Director's Guide](https://onlineobservation.com/docs/directors_guide/en/)

**2. Agent and ops design.**
I split AI work into roles so that one agent's mistake gets caught by another before it reaches me: a planner, a reviewer who argues against the plan, a checker for facts, and so on. Six such agents are in use in my production work. How it is set up, and what failed along the way: [ai-ops-playbook](https://github.com/masato221/ai-ops-playbook)

**3. Japanese.**
Rating and correcting Japanese AI output as a trainer on AI training platforms. Platform names, task counts and ratings are available on request.
(I don't name clients or describe task content, out of respect for platform terms and NDAs.)

日本語の評価は、AIトレーニングのプラットフォームでトレーナーとして活動した実績です。社名や課題の中身は規約・NDAのため書きません。

## Numbers

- 8,932 GitHub contributions in the past year (as of 2026-10-30, includes private repositories)
- 21 private repositories built with AI, 10,385 commits in total (as of 2026-10-30)
- 6 AI agents, each with a separate role

These count activity, not quality. The evaluation work is in the three sections above.

## Contact

Site: [onlineobservation.com](https://onlineobservation.com)

過去1年のcontributionsは8,932件(非公開リポジトリ含む)、AIと作った非公開リポジトリは21本・commit計10,385件、役割を分けたAI agentは6種です。件数は活動量であって品質ではありません。
