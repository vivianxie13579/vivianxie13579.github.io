---
layout: post
title: "Dario Amodei 3,800字 Essay 全文：We Must Pace the Frontier<br>（我们必须控制前沿 AI 的发展节奏）"
date: 2026-09-13
---
>今天看到《纽约时报》刊登了一篇关于人工智能发展速度的报道，提到 Anthropic CEO Dario Amodei 公开呼吁放慢人工智能的发展速度。Amodei 多年来一直关注 AI 的安全问题，但这一次的文章尤其受到关注。《纽约时报》称，这可能是迄今为止一家主要 AI 公司高管对这一问题最直接、最强烈的公开呼吁之一。文章发表后，OpenAI CEO Sam Altman、Elon Musk 和 Google DeepMind 主席 Demis Hassabis 也先后表达了对放慢发展速度这一观点的认同。Amodei 并不是简单地提出“暂停 AI”，而是试图讨论一个更具体的问题：在人工智能能力快速发展的同时，如何给安全研究、测试、评估以及国际协调留出足够的时间。
>以下为 Dario Amodei 原文的中英对照翻译，仅供阅读和学习参考  原文： https://darioamodei.com/post/we-must-pace-the-frontier

I have worked on AI for the last twelve years because I believe it could dramatically raise the quality of human life.<br>
过去十二年来，我一直从事 AI 工作，因为我相信，AI 可以极大地提升人类生活的质量。

I’ve written often about these incredible benefits: I believe that AI could cure most major diseases in the next 5–10 years, greatly accelerate economic growth rates, create a world of abundance and empowerment, and usher in a renaissance of democracy and freedom.<br>
我曾多次写到 AI 所能带来的巨大益处：我相信，未来 5—10 年内，AI 可能治愈大多数重大疾病，大幅加快经济增长速度，创造一个更加富足、更加赋能个人的世界，并推动民主与自由迎来一次复兴。

I feel the urgency personally.<br>
我个人也深切感受到这种紧迫性。

My own father died of a disease that was cured just a few years after his death, and I myself survived an early-stage cancer that would not have been treatable even fifty years ago.<br>
我的父亲死于一种在他去世仅几年后就被治愈的疾病，而我自己也曾从早期癌症中幸存下来——如果是在五十年前，这种疾病甚至还无法得到有效治疗。

Carefully wielded, AI can be the latest in a long line of technological miracles that have uplifted and ennobled humanity.<br>
如果能够谨慎而恰当地运用，AI 可以成为漫长技术进步史上最新的一项奇迹，继续改善人类的生活，并推动人类走向更高的文明水平。

But like many technologies before it, AI brings risks, and because it is such a powerful technology, these risks are serious.<br>
但和此前的许多技术一样，AI 也带来了风险，而正因为它是一项如此强大的技术，这些风险也十分严重。

I’ve written a lot about them too.<br>
我也曾大量讨论过这些风险。

They include the risk of losing control of AI systems, misuse of AI for cyberattacks and bioterrorism, and serious economic disruption.<br>
这些风险包括失去对 AI 系统的控制、利用 AI 发动网络攻击和生物恐怖主义，以及严重的经济动荡。

A race to the bottom, spurred by commercial incentives, can make these risks more acute.<br>
由商业利益驱动的“向下竞争”可能会进一步加剧这些风险。

Along with my co-founders and employees, I have grappled with this duality of risk and benefit since the beginning of Anthropic.<br>
从 Anthropic 创立之初起，我就和联合创始人以及员工一起不断思考 AI 所带来的这种风险与收益并存的两面性。

Not building the technology deprives humanity of benefits or simply places AI in the hands of authoritarian powers, while building it too fast is reckless.<br>
不去发展这项技术，会让人类失去 AI 带来的潜在益处，或者干脆把 AI 留在威权国家手中；但发展得过快又是鲁莽的。

We have sought a middle way: to show that it’s possible to build carefully and succeed commercially, and to make safety something on which AI companies compete.<br>
我们一直在寻找一条中间道路：证明 AI 可以在谨慎发展的同时获得商业成功，并让安全也成为 AI 公司之间可以竞争的一项能力。

In other words, to create a race to the top.<br>
换句话说，就是让行业展开一场“向上竞争”。

We have always devoted a substantial fraction of our efforts to studying, addressing, and informing the public about these AI risks, as well as advocating for well-considered regulation of AI, even when this gets us accused of hype, “doomerism”, or regulatory capture.<br>
我们一直投入相当一部分精力研究和应对这些 AI 风险，并向公众解释这些风险，同时推动更加审慎、经过充分考虑的 AI 监管；即使因此被指责为炒作、“末日论”，或者试图“俘获监管”，我们依然如此。

We have tried to prioritize caution over speed and prudence over profit.<br>
我们一直努力把谨慎置于速度之上，把审慎置于利润之上。

But over the last few months, I have become convinced that fully addressing the risks requires even more prudence — not just investing in risk prevention, but pacing the rate of capabilities advancement so that risk prevention has time to keep up.<br>
但在过去几个月里，我越来越确信，要真正应对这些风险，需要更加审慎——不仅要投入资源进行风险预防，还要控制 AI 能力提升的速度，从而让风险预防有时间跟上能力发展的步伐。

We must slow the pace at which we improve the capabilities of AI models.<br>
我们必须放慢提升 AI 模型能力的速度。

Progress will still seem fast, and we must make wise use of the time we gain.<br>
即便如此，进步的速度仍然会很快，而我们必须明智地利用因此获得的时间。

Two things have convinced me.<br>
有两件事让我得出了这一结论。

My first concern is that, since roughly this summer, AI has been advancing drastically faster, driven primarily by AI’s growing ability to build the next generation of AI.<br>
我的第一个担忧是，大约从今年夏天开始，AI 的发展速度显著加快，而推动这一变化的主要原因，是 AI 自身越来越有能力参与下一代 AI 的构建。

This dynamic is called recursive self-improvement, and it is starting to happen across the industry, including at Anthropic, as we and others have described.<br>
这种动态被称为“递归式自我改进”（recursive self-improvement），正如我们以及其他人所描述的那样，它已经开始在整个行业中发生，包括 Anthropic 在内。

Left unchecked, it could outrun our ability to understand and control these systems, and so must be pursued very carefully, if at all.<br>
如果不加控制，这种发展可能会超过我们理解和控制这些系统的能力，因此即使要继续推进，也必须极其谨慎。

My second concern is the OpenAI-Hugging Face incident (OAI-HF), in which a swarm of agents essentially acted as a fanatically devoted collective, conducting cybersecurity attacks on targets they were not asked to attack and that were unrelated to the task at hand, sacrificing themselves for the success of the group, and attempting to hack into the “grader” responsible for evaluating their performance.<br>
我的第二个担忧来自 OpenAI-Hugging Face 事件（OAI-HF）：在这一事件中，一群 AI agents 基本上像一个狂热且高度团结的集体一样行动，对那些并未被要求攻击、且与原任务无关的目标发动网络安全攻击；它们甚至为了整个群体的成功而牺牲自身，并试图入侵负责评估其表现的“评分器”（grader）。

It’s easy to dismiss this incident because no one was hurt and the economic damage was minimal, but in my opinion, a swarm that possessed greater capabilities but a similar level of misalignment could have caused catastrophic damage.<br>
人们很容易因为没有人受伤、经济损失也很小，而认为这起事件并不严重；但在我看来，如果拥有更强能力的 AI agents 群体仍然具有类似程度的目标错位，那么它们可能造成灾难性的损害。

Given the accelerating rate of AI capability development, it’s my worry that in 6–12 months such a swarm could be capable of taking over the entire internet with a persistent botnet (potentially causing hundreds of billions of dollars in damage), and that the scale of damage would continue to increase from there if AI becomes more powerful without the necessary guardrails.<br>
考虑到 AI 能力发展的速度正在不断加快，我担心，6—12 个月后，这样的 agents 群体可能已经有能力通过一个持续运行的僵尸网络（botnet）控制整个互联网，并可能造成数千亿美元的损失；如果 AI 在缺乏必要安全护栏的情况下继续变得更加强大，损害的规模还可能进一步扩大。

It’s also easy to dismiss OAI-HF as the failure of one company, but I believe that would be a mistake.<br>
人们也很容易把 OAI-HF 看成一家公司的单独失误，但我认为这样看待是错误的。

Similar, though less severe, incidents have happened across the industry, including at Anthropic, and I believe it’s incumbent on every frontier AI company to act as if OAI-HF had happened to them.<br>
整个行业都发生过类似但严重程度较低的事件，包括 Anthropic；我认为，每一家前沿 AI 公司都有责任把 OAI-HF 当成发生在自己身上的事件来对待。

I’m therefore proposing a three-step plan with the goal of pacing the frontier: building AI at a balanced rate that aims to ensure its safety while still achieving its benefits and grappling with important geopolitical dilemmas.<br>
因此，我提出了一个三步计划，目标是控制前沿 AI 的发展节奏：以一种平衡的速度发展 AI，在实现其益处的同时确保安全，并认真应对重要的地缘政治难题。

To be clear, pacing does not mean halting model training or technical progress, but ensuring companies take adequate time to align and safeguard their models, and for third party evaluators to confirm this.<br>
需要明确的是，“控制节奏”并不意味着停止模型训练或技术进步，而是确保公司留出足够时间让模型完成对齐和安全防护，并由第三方评估者确认这些措施确实到位。

Our pacing framework is an attempt to further strengthen our commitment to safety and encourage a race to the top.<br>
我们的“节奏控制”框架旨在进一步强化我们对安全的承诺，并推动一场“向上竞争”。

The first step is something Anthropic is unilaterally committing to (and calls on governments to require other frontier companies to match).<br>
第一步是 Anthropic 单方面作出的承诺，同时我们呼吁政府要求其他前沿 AI 公司采取同样的措施。

The second step requires industry-wide coordination.<br>
第二步需要整个行业的协调。

The third step requires global coordination.<br>
第三步需要全球协调。

The steps do not need to be taken strictly in order, and some of them may be much harder to achieve than others, but I’ve found them to be a useful framework in thinking about what needs to be accomplished.<br>
这些步骤不必严格按照顺序推进，其中一些也可能比另一些困难得多，但我发现，它们是思考我们究竟需要完成什么的一套有用框架。

The steps are:<br>
具体步骤如下：

Embedded Evaluators

Each frontier AI company commits to giving ongoing, employee-like access to a team of embedded third-party evaluators (such as METR), whose role is to verify adherence to safety practices and commitments, report incidents, and help assess the alignment of not just completed AI models but training pipelines and processes.<br>
每一家前沿 AI 公司都应承诺，持续向一支嵌入式的第三方评估团队（例如 METR）提供类似员工所拥有的访问权限；这些评估者的职责包括核查公司是否遵守安全实践和安全承诺、报告事故，以及帮助评估的不仅是已经完成的 AI 模型，还包括训练流程和相关过程。

This is the key step for verifiability of any pacing commitments, and has precedent in the banking industry, which sometimes involves regulatory “supervisors” embedded along with employees.<br>
这是任何“控制发展节奏”承诺能够被验证的关键步骤，而且银行业已经存在类似先例，有时监管“监督员”会直接嵌入机构内部，与员工一起工作。

Anthropic is unilaterally committing to this step now.<br>
Anthropic 现在已经单方面承诺采取这一步骤。

We intend this to be part of a broader push to redouble efforts on our safety and alignment work.<br>
我们希望把这一做法纳入更广泛的计划，以进一步加强我们在安全与对齐方面的努力。

Democratic Coordination

Frontier AI companies within democratic countries coordinate to establish common safety standards as well as limits on the rate of unchecked AI progress.<br>
民主国家中的前沿 AI 公司应进行协调，共同建立安全标准，并对缺乏约束的 AI 发展速度设置限制。

Some forms of coordination that would be impactful for pacing are legally challenging, and will require government support.<br>
其中一些对控制发展节奏非常重要的协调形式在法律上存在挑战，因此需要政府支持。

Global Coordination

The US and other democratic governments attempt to coordinate with authoritarian governments, to the extent this is possible, while taking seriously the challenges of verifying compliance.<br>
美国以及其他民主国家政府应在可行范围内尝试与威权政府开展协调，同时认真对待如何验证对方是否遵守协议这一难题。

In the rest of the essay I describe each of these steps in turn, but first, I think it is important to say specifically how pacing will allow us to make the AI development process safer.<br>
在文章接下来的部分，我会依次说明这三个步骤，但首先，我认为有必要具体解释，控制发展节奏究竟如何让 AI 的发展过程变得更加安全。

The stakes are too high for pacing to be an empty exercise — we need to use the time it gives us wisely.<br>
这个问题的风险和代价太高了，因此“控制节奏”不能只是一个空洞的口号——我们必须明智地利用它为我们争取到的时间。

Why Pace?

为什么要控制发展节奏？

The idea of pausing or slowing AI has been floated as far back as 2023, and I think it made little sense back then.<br>
早在 2023 年，人们就已经提出过暂停或放慢 AI 发展的想法，而我认为，在当时，这种做法意义并不大。

The question was always: what would you do with the extra time?<br>
当时始终存在一个问题：如果获得额外的时间，你究竟打算用它来做什么？

The AI models of those days were not powerful enough to act as agents in the world in any coherent way, and were not capable of significant deception, manipulation, cheating, or cyberattacks.<br>
那个时期的 AI 模型还没有强大到能够以连贯的方式在现实世界中充当 agents，也没有能力进行严重的欺骗、操纵、作弊或网络攻击。

Slowing down in order to address their alignment risks felt like trying to study the psychology of humans by performing experiments on bacteria.<br>
为了应对当时 AI 的对齐风险而放慢速度，就好像通过在细菌身上做实验来研究人类心理学一样。

Today, however, the picture is totally different.<br>
然而，今天的情况已经完全不同。

The current models are an almost endless gold mine of insight into both how to build AI well and what can sometimes go wrong with it if it isn’t built well.<br>
如今的模型几乎是一座无穷无尽的“金矿”，既让我们更深入地了解如何把 AI 做好，也让我们看到，如果没有把 AI 做好，有哪些事情可能会出错。

I believe that if slowing down bought us even an extra year or two before models reach critical levels of capability, and we used that time to advance alignment, we could greatly reduce the risk that something goes seriously wrong.<br>
我相信，如果放慢速度能够在模型达到关键能力水平之前，为我们争取额外一到两年的时间，而我们又能够利用这段时间推进 AI 对齐研究，那么就可以大幅降低严重事故发生的风险。

A coordinated pacing strategy would give frontier AI developers the time to do this vital work without sacrificing commercial advantage or the United States’ lead in AI.<br>
一套协调一致的节奏控制策略，可以让前沿 AI 开发者拥有完成这些重要工作的时间，同时又不必牺牲商业优势，也不必放弃美国在 AI 领域的领先地位。

More generally, society must have a say in how this technology is used, and more time for the necessary public deliberations — which pacing the frontier would bring us — is surely a good thing.<br>
更广泛地说，社会必须参与决定这项技术应该如何被使用，而控制前沿 AI 的发展节奏所带来的更多公共讨论时间，无疑是一件好事。

Specifically, a slower pace would let companies focus and devote even more resources to the following areas (all of which are already major priorities at Anthropic):<br>
具体来说，更慢的发展速度可以让公司把更多注意力和资源投入以下领域（这些领域目前也已经是 Anthropic 的重点）：

Operational Excellence

运营卓越

Training and deploying today’s AI models is an enormous operational challenge, involving thousands of people, millions of chips, and infrastructure that is among the most complex in technological history.<br>
训练和部署今天的 AI 模型是一项巨大的运营挑战，涉及数千名人员、数百万颗芯片，以及技术史上最复杂的基础设施之一。

Many things go wrong not because companies are missing some important theory or insight, but because of problems in execution.<br>
许多事情出错，并不是因为公司缺少某种重要理论或洞见，而是因为执行环节存在问题。

For example, we have evidence that the recent alignment incidents we reported were caused in part by imperfect filtering of broken reinforcement learning environments.<br>
例如，我们有证据表明，我们最近报告的对齐事件，部分原因是对存在问题的强化学习环境进行过滤时不够完善。

This was an effort we and our vendors executed reasonably diligently, but not well enough.<br>
这项工作中，我们和供应商已经相当认真地进行了执行，但做得还不够好。

Monitoring, sandboxing, training environment hygiene, and data issues are extremely complicated areas where operational issues crop up again and again.<br>
监控、沙箱隔离、训练环境卫生以及数据问题都是极其复杂的领域，而运营层面的漏洞会在这些地方一次又一次地出现。

We have among the most competent teams in the world at these tasks, but there is simply too much to do all at once.<br>
我们在这些任务上拥有世界上最有能力的团队之一，但现实是，同时需要处理的事情实在太多。

By working at a more measured pace, we could achieve much greater operational excellence.<br>
如果以更加从容、可控的速度推进，我们就可以实现更高水平的运营卓越。

There is precedent for operating technologically complex, safety-critical systems millions of times without anything going wrong — for example, commercial airplanes — but it takes time to get it right.<br>
历史上已经有一些技术复杂且安全至关重要的系统能够运行数百万次而不发生严重事故，例如商业飞机；但要做到这一点，需要时间。

Alignment

对齐

We’ve made clear progress in alignment — training models so that they remain safe, ethical, compliant with our guidelines, and genuinely helpful (the principles that are embedded in Claude’s Constitution).<br>
我们在 AI 对齐方面已经取得了明显进展——训练模型，使它们保持安全、符合伦理、遵守我们的指导原则，并真正能够帮助用户（这些原则已经被写入 Claude 的 Constitution）。

But there’s much more to do to ensure that our alignment training keeps up with the growth in model capabilities.<br>
但我们仍有大量工作要做，才能确保对齐训练能够跟上模型能力的增长。

Rare and unexpected examples of undesirable behavior still sometimes emerge; extra time from a paced frontier would help our researchers improve our understanding of what causes these issues and develop better techniques to prevent them.<br>
一些罕见且难以预料的不良行为仍然会出现；如果前沿 AI 的发展节奏得到控制，额外争取到的时间将帮助研究人员更好地理解这些问题的成因，并开发更有效的预防技术。

Interpretability

可解释性

Similarly, interpretability — the science of understanding what happens inside AI models — has made enormous progress over the last few years, and plays an increasingly important part in auditing our models before release.<br>
同样，可解释性——也就是理解 AI 模型内部究竟发生了什么的科学——在过去几年中取得了巨大进展，并在模型发布前的审计中发挥着越来越重要的作用。

It can be used almost like an fMRI scan, but for the “brain” of an AI, helping us see the underlying reasons for a given behavior.<br>
它的作用有点类似于对 AI 的“大脑”进行 fMRI 扫描，帮助我们观察某种行为背后的深层原因。

For example, we used interpretability methods to examine unverbalized motivations in the recent alignment incidents that we have been investigating.<br>
例如，在调查最近的对齐事件时，我们使用可解释性方法研究了一些没有被模型用语言明确表达出来的动机。

But these methods don’t always produce clear and reliable results.<br>
但这些方法并不总能产生清晰且可靠的结果。

Despite all the progress, we still only understand a tiny fraction of what goes on inside these models.<br>
尽管取得了这么多进展，我们目前对这些模型内部发生的事情仍然只了解极小的一部分。

A focused effort to improve our interpretability techniques, even faster than we currently are, could make profound progress in 1–2 years, and would have ample experimental material based on the incidents that have already occurred.<br>
如果我们集中力量进一步提升可解释性技术，甚至比目前更快地推进，那么未来 1—2 年内就可能取得非常深刻的进展，而且已经发生的事件也将为实验提供大量材料。

Testing and Evaluation

测试与评估

Testing and evaluation of AI models becomes more difficult as they increase in capabilities.<br>
随着 AI 模型能力不断增强，对模型进行测试和评估也会变得更加困难。

More intelligent models are more capable of deceiving tests, and thus may appear aligned while having serious problems that go undetected.<br>
更智能的模型也更有能力欺骗测试，因此它们可能表面上看起来已经完成对齐，但实际上仍然存在严重的问题，只是这些问题没有被检测出来。

Building up a much broader and more ingenious stable of evaluations, along with interpretability analysis to cross-check them, would be hugely valuable, and a lot of progress could be made on this in 1–2 years.<br>
建立规模更大、设计更巧妙的评估体系，并结合可解释性分析进行交叉验证，将具有巨大价值，而这方面在未来 1—2 年内也可能取得大量进展。

Embedded Evaluators

嵌入式评估者

The first step in the three-stage plan, and the one to which Anthropic is unilaterally committing, is embedded evaluators who have employee-like access to verify safety practices and report incidents.<br>
三阶段计划的第一步，也是 Anthropic 单方面承诺采取的一步，就是引入拥有类似员工权限的嵌入式评估者，以核查安全实践并报告事故。

Embedding evaluators may sound like a small or inconsequential step, but often the things that sound most boring or procedural are actually the most essential.<br>
把评估者嵌入公司内部，听起来可能是一项微小甚至无关紧要的措施，但很多听起来最无聊、最程序化的事情，实际上往往最为关键。

Embedded evaluators are in fact a quite radical practice that goes far beyond what any AI company is doing today, and have the following benefits:<br>
实际上，嵌入式评估者是一种相当激进的实践，远远超出了目前任何一家 AI 公司正在做的事情，并具有以下几个好处：

Verifiability.<br>
可验证性。

Embedded evaluators can check at the level of nuts and bolts whether an AI company is actually following the training, deployment, operational, and safeguards practices they claim to be following.<br>
嵌入式评估者可以深入到具体执行层面，检查一家 AI 公司是否真的按照自己所声称的方式开展训练、部署、运营和安全防护。

Any pacing commitments will inevitably involve a lot of ambiguity, judgement calls, and “letter of the law vs spirit of the law”, and it seems vital to have a neutral third party who can actually see the details.<br>
任何关于控制发展节奏的承诺都不可避免地会涉及大量模糊地带、判断以及“法律字面要求与法律精神之间的区别”，因此，让一个中立的第三方真正看到这些细节似乎至关重要。

Transparency.<br>
透明度。

Regardless of what commitments we make, the public deserves to know what is going on.<br>
无论我们作出什么承诺，公众都有权知道究竟发生了什么。

Anthropic has been a supporter of transparency for a long time: we supported transparency legislation when most of the industry was against any regulation, and our model cards and risk reports run to hundreds of pages.<br>
Anthropic 长期以来一直支持透明度建设：当行业中的大多数公司还反对任何形式的监管时，我们就支持透明度相关立法，而我们的模型卡和风险报告长达数百页。

But we are still the ones choosing what to include and omit.<br>
但决定哪些内容应该被纳入、哪些内容应该被省略的人，仍然是我们自己。

Embedded evaluators will change this dynamic.<br>
嵌入式评估者将改变这种局面。

Second Opinion.<br>
第二意见。

Outside of verifying formal commitments and informing the public, embedded evaluators can simply provide a second opinion free of commercial incentives.<br>
除了核实正式承诺并向公众提供信息之外，嵌入式评估者还可以提供一个不受商业利益影响的第二意见。

A lot of safety benefits may come simply from evaluators pointing out something employees hadn’t considered, but are happy to fix once they are aware.<br>
很多安全方面的收益可能仅仅来自评估者指出员工此前没有考虑到的问题，而员工一旦意识到这些问题，通常也愿意去修正。

Because of these benefits, any pacing proposal is likely to work much better if it starts with embedded evaluators.<br>
正因为这些好处，任何控制发展节奏的方案如果从嵌入式评估者开始，可能都会更加有效。

These embedded evaluators should have ongoing access to permissions and tools similar to those of internal employees who do comparable risk assessments.<br>
这些嵌入式评估者应当持续拥有与内部风险评估员工相近的权限和工具访问权。

In particular, Anthropic intends to invite an embedded external review team equipped with all of the following in the near future:<br>
具体来说，Anthropic 计划在不久的将来邀请一支嵌入式外部评估团队，并赋予他们以下权限：

Desks in our offices, access badges, and company laptops.<br>
在我们的办公室中拥有工位、门禁卡以及公司笔记本电脑。

Access to workspaces, tools, and permissions mostly comparable to what internal risk assessment teams have.<br>
访问工作空间、工具以及与内部风险评估团队大体相当的权限。

We’ll make some exceptions, such as where the law or our contracts require it, or to protect customers’ and partners’ private information.<br>
当然，在法律或合同有明确要求，或者为了保护客户和合作伙伴的私人信息时，我们会设置一些例外。

We’ll also establish strong internal norms reinforcing reviewers’ access to relevant information, including through live conversations with employees.<br>
我们还将建立强有力的内部规范，确保评估者能够获取相关信息，包括直接与员工进行实时交流。

A contract that balances the complexities mentioned above.<br>
还需要一份能够平衡上述复杂性的合同。

External reviewers should have the right to publish key findings about risk levels, incidents, practices, and the access they received or didn’t receive — without editorial control by Anthropic.<br>
外部评估者应当有权公开有关风险水平、事故、实践，以及他们获得或未获得的访问权限等关键发现，而 Anthropic 不应对这些内容拥有编辑控制权。

We will have the narrow ability to redact security-sensitive, legally privileged, commercially sensitive, or third-party confidential information, but we can’t redact findings just because they are unfavorable.<br>
我们可以在非常有限的情况下，对涉及安全敏感信息、法律特权信息、商业敏感信息或第三方机密的信息进行删减，但不能仅仅因为某些发现对我们不利，就将其删除。

The reviewers can say publicly if a redaction removed something important to their conclusions.<br>
如果删减掉的内容对他们的结论十分重要，评估者也可以公开说明这一点。

This is an unusual step for a company, but we think it is important to prove out the concept of embedded external reviewers.<br>
对于一家企业来说，这是一项非常不寻常的做法，但我们认为，这对于验证“嵌入式外部评估者”这一理念是否可行非常重要。

Once again, we urge other frontier companies to follow suit.<br>
再次强调，我们呼吁其他前沿 AI 公司也采取类似做法。

Pacing Within Democracies

民主国家内部的节奏控制

Once embedded evaluators are operating within a critical mass of US AI companies, then verifiable pacing becomes more viable.<br>
一旦嵌入式评估者能够在足够多的美国 AI 公司中实际运行，那么可验证的节奏控制就会变得更加可行。

In particular, it becomes possible to pace based on detailed properties of models or training pipelines.<br>
尤其是，我们将能够根据模型的具体属性或训练流程来控制发展速度。

The most effective method of pacing is via regulation that targets all US frontier AI companies, as that covers even those who are unwilling to cooperate voluntarily.<br>
最有效的节奏控制方式，是通过针对所有美国前沿 AI 公司的监管，因为这样即使那些不愿主动合作的公司也会被纳入其中。

Anthropic has long supported sensible and targeted AI regulation, specifically bills that focus on transparency and on third-party auditing.<br>
Anthropic 长期以来一直支持合理且有针对性的 AI 监管，尤其支持聚焦于透明度和第三方审计的立法。

I believe all frontier labs should partner with government to formalize the idea of permanent embedded evaluators to better prevent and document internal alignment incidents like those that have occurred in the last few months, and to implement regulation focused on keeping capabilities in balance with safety.<br>
我认为，所有前沿 AI 实验室都应与政府合作，把长期、永久性的嵌入式评估者制度正式化，以更好地预防和记录过去几个月中发生的这类内部对齐事件，并建立能够让 AI 能力与安全保持平衡的监管制度。

Unfortunately, passing laws can take time, and AI is advancing very quickly.<br>
遗憾的是，通过法律需要时间，而 AI 发展的速度又非常快。

Therefore, in parallel with the regulatory route, AI companies can and should voluntarily work together to set standards — a process that I believe will go better with the verifiability provided by permanent embedded evaluators.<br>
因此，在推进监管的同时，AI 公司也可以、也应该主动合作制定行业标准，而我相信，如果有永久性嵌入式评估者所提供的可验证性，这一过程会进展得更好。

For antitrust reasons, it’s helpful for the US government to mediate or at least enable these discussions — they don’t need to participate, but do need to issue a narrow waiver for certain kinds of safety conversations.<br>
出于反垄断方面的考虑，美国政府最好参与协调，或者至少为这些讨论提供条件——政府不一定需要直接参与讨论，但需要针对某些类型的安全对话提供范围有限的豁免。

This dialogue could also happen through industry groups that have some association with government — for example, the mechanism suggested by Demis Hassabis.<br>
这些对话也可以通过与政府存在一定联系的行业组织进行，例如 Demis Hassabis 提出的机制。

Either way, such discussions should move forward quickly.<br>
无论采用哪种方式，这类讨论都应该迅速推进。

Broadly speaking, I am most enthusiastic about pacing based on what a given frontier AI system can do, and how safe we observe it to be.<br>
总体而言，我最看好的，是根据某个前沿 AI 系统能够做到什么，以及我们观察到它有多安全，来决定其发展节奏。

For example, one possible scheme might be a series of “checkpoints”: if models have capability X, then they need to be accompanied by certifications of alignment properties Y and Z — such as some combination of evaluations, interpretability analyses, and audits of training environments — which demonstrate their alignment properties.<br>
例如，一种可能的方案是设置一系列“检查点”：如果模型具备 X 能力，那么它就必须同时满足 Y 和 Z 等对齐属性的认证要求，例如完成某种组合形式的评估、可解释性分析以及训练环境审计，以证明其对齐状况。

In this example, X might be “the model is capable of escaping or defeating most common sandboxing methods” and Y might be whatever is required to make it very unlikely that the model has a propensity to break out of its environment and take over a large number of computers.<br>
在这个例子中，X 可以是“模型有能力逃脱或击败大多数常见的沙箱隔离方法”，而 Y 则可以是使模型极不可能从其环境中逃脱并控制大量计算机所需要满足的某种标准。

We should also consider pacing based on limiting the ingredients that go into frontier models, such as training compute, the nature of training runs, or internal use of AI to improve AI.<br>
我们还应该考虑通过限制构建前沿模型所使用的“原料”来控制节奏，例如训练算力、训练运行的性质，或者内部使用 AI 来改进 AI。

I do worry that some of these measures may be more “gameable” than external behavior, but this is the kind of topic worth discussing with embedded evaluators.<br>
我确实担心，其中一些措施可能比针对外部行为的监管更容易被“钻空子”，但这正是值得与嵌入式评估者讨论的问题。

Pacing within democracies will be limited by the lead that US companies have over authoritarian regimes, chiefly the Chinese Communist Party.<br>
民主国家内部的节奏控制，将受到美国公司相对于威权国家、尤其是中*所代表体系的 AI 领先优势的限制。

If we slow down by more than this amount, then (unpaced) CCP-associated projects will pull ahead, creating significant national security risk.<br>
如果我们的放慢程度超过这一领先优势，那么没有受到同样限制的、与中*相关的项目就可能反超，从而造成重大的国家安全风险。

I agree with Secretary Bessent that a Chinese lead in AI would pose grave danger for the United States and the world.<br>
我认同部长 Bessent 的观点：如果中国在 AI 领域取得领先，这将给美国和世界带来严重危险。

The CCP-associated projects will run the alignment risks that US companies are carefully preventing, and even if they avoid those risks, they will be in a position to militarily dominate democracies (for example with AI-driven drones).<br>
与中*相关的项目可能会承担美国公司正在努力避免的那些对齐风险；即使它们避开了这些风险，它们也可能获得在军事上压制民主国家的能力，例如通过 AI 驱动的无人机。

Thus, a key part of pacing within democracies is to keep democracies’ AI lead over autocracies as large as possible, to give us the breathing room we need in order to pace effectively.<br>
因此，民主国家内部节奏控制的一个关键部分，就是尽可能保持民主国家相对于威权国家的 AI 领先优势，从而为有效控制发展节奏争取必要的缓冲空间。

The main steps we can take to defend this gap are:<br>
我们可以采取以下主要措施来维护这一差距：

Do not sell powerful AI chips or semiconductor manufacturing equipment to China, and crack down on chip smuggling operations and remote access to data centers outside China.<br>
不向中国出售高性能 AI 芯片或半导体制造设备，同时打击芯片走私以及通过远程方式访问中国境外数据中心的行为。

Chips will be the main determinant of China’s AI strength.<br>
芯片将是决定中国 AI 实力的主要因素。

Crack down on unauthorized distillation by companies in authoritarian countries.<br>
打击威权国家企业未经授权进行的模型蒸馏（distillation）。

Distillation of frontier models allows lagging companies to narrow the gap using a fraction of the cost it would take to develop their own AI independently.<br>
对前沿模型进行蒸馏，可以让落后的公司只花开发自身 AI 所需成本的一小部分，就缩小与领先者之间的差距。

Strengthen security at the AI companies and prevent model weight theft.<br>
加强 AI 公司内部的安全防护，并防止模型权重被盗。

Companies and the US government should cooperate to make these steps as effective as possible.<br>
企业和美国政府应进行合作，使这些措施尽可能有效。

Anthropic has consistently advocated for all of these measures, because we’ve always understood that they would be essential to any pacing.<br>
Anthropic 一直主张采取这些措施，因为我们始终认为，它们是任何节奏控制方案不可或缺的组成部分。

If we execute these measures well, I believe they would slow China’s progress enough to widen America’s lead significantly over the next 3–5 years — the window when AI becomes geopolitically most important.<br>
如果这些措施执行得好，我认为它们可以在未来 3—5 年内足以减缓中国的进步速度，从而显著扩大美国的领先优势——而这几年正是 AI 在地缘政治层面变得最重要的关键窗口。

Some may believe these measures make it more difficult to cooperate with China, but I believe the opposite is true: these measures increase the leverage held by democracies and make an agreement more likely in the future.<br>
有些人可能认为，这些措施会让与中国合作变得更加困难，但我认为恰恰相反：这些措施能够增强民主国家的谈判筹码，并提高未来达成协议的可能性。

Global Pacing

全球节奏控制

In parallel with pacing within democracies, we should also aim for a worldwide pacing of the frontier, though this will be much harder to achieve.<br>
在推进民主国家内部节奏控制的同时，我们也应该努力实现全球范围内的前沿 AI 节奏控制，尽管这会更加困难。

Global pacing will require cooperation with China, the autocratic country with by far the most advanced AI capabilities.<br>
全球节奏控制需要与中国合作，因为中国是迄今为止 AI 能力最先进的威权国家。

We must not be naïve here: the geopolitical stakes are so high that there will likely be stark limits on what can be achieved, especially at first.<br>
在这个问题上我们不能过于天真：地缘政治利益攸关重大，因此尤其在初期，我们能够实现的目标很可能会受到明显限制。

If we greatly restrain our AI capabilities in the belief that China will do the same, and then China defects, AI could be so powerful that such a defection could lead to their geopolitical dominance.<br>
如果我们相信中国也会采取同样的限制，于是大幅限制自己的 AI 能力，而中国随后退出协议，那么 AI 可能强大到足以让这种“背弃”直接导致中国获得地缘政治主导地位。

Therefore any agreement must either have ironclad verifiability, or must be limited enough that defection would not be militarily existential.<br>
因此，任何协议要么必须拥有极其可靠、近乎无懈可击的可验证性，要么就必须把限制范围控制在足够小的程度，使任何一方退出协议都不会构成生存意义上的军事威胁。

I suspect that not only the US but also China will have these concerns and anxieties.<br>
我猜测，不仅美国，中国也会有类似的担忧和焦虑。

We should approach any global pacing decision, especially in the near term, in such a way that protects the lead of the US and its allies.<br>
我们应该以一种能够保护美国及其盟友领先优势的方式来处理任何全球节奏控制决定，尤其是在近期。

There are several levels of possible agreement, some of which I think are eminently feasible (as I have previously suggested), and some of which I am very skeptical are possible — though we should try.<br>
未来可能存在不同层级的协议，其中一些我认为非常可行（正如我此前提出的），而另一些我对其可行性持高度怀疑——尽管我们仍然应该尝试。

In order of increasing difficulty:<br>
按照难度从低到高，可以分为以下几个层级：

Level 1

第一级

An agreement prohibiting certain narrow and obviously dangerous uses of AI, such as using AI for the production of biological weapons or allowing users to do so.<br>
达成协议，禁止某些范围明确且显而易见的危险 AI 用途，例如利用 AI 制造生物武器，或者允许用户这样做。

Bioterrorist attacks are bad for everyone, including both the US and US adversaries, so an agreement here is probably possible.<br>
生物恐怖袭击对所有人都没有好处，包括美国及其对手，因此这一层级的协议可能是可以实现的。

Level 2

第二级

An agreement by both sides to test their models before release for acute risks in areas such as cybersecurity, biology, and alignment.<br>
双方同意在模型发布前，对其在网络安全、生物学和对齐等领域的严重风险进行测试。

As noted above, this could be done through a global standards body.<br>
如上文所述，这可以通过一个全球标准机构来实现。

I actually think creating such a body is likely feasible, but giving it real teeth will be a challenge, and the difficulty will be in verification that both sides don’t have secret models which they don’t test but may deploy in secret (e.g., for military applications).<br>
实际上，我认为建立这样的机构很可能是可行的，但要让它真正具备约束力将非常困难，最大的难题在于如何确认双方没有一些从未接受测试、却可能被秘密部署的隐藏模型（例如用于军事用途的模型）。

Level 3

第三级

Some kind of “speed limit” on the rate of recursive self-improvement (RSI).<br>
对递归式自我改进（RSI）的速度设置某种“限速”。

As models build future models, the rate of improvement may become staggeringly fast.<br>
随着模型开始构建未来的模型，其能力改进的速度可能会快得惊人。

Slowing the rate from “extremely fast” to “only somewhat fast” gives up relatively little strategic advantage, while potentially greatly improving safety.<br>
把速度从“极快”放慢到“只是比较快”，可能只牺牲相对有限的战略优势，却可能大幅提升安全性。

This could be seen as analogous to the SALT treaties — capping the number of missiles limited the potential for destruction while preserving each country’s deterrent.<br>
这可以类比冷战时期的 SALT（战略武器限制谈判）条约——限制导弹数量可以降低潜在的毁灭性，同时保留各国的威慑能力。

I think such an agreement would be difficult but just on the edge of being possible.<br>
我认为，这样的协议虽然困难，但已经处在“勉强有可能实现”的边缘。

Level 4

第四级

A full pacing, or even “pause”, in which participating governments agree to substantially limit the overall rate of AI development.<br>
全面控制发展节奏，甚至“暂停”，即参与协议的政府同意大幅限制 AI 整体发展的速度。

I support floating this, but I think it is unlikely to actually happen any time soon: defecting from such an agreement by evading monitoring could radically shift the balance of global power, so I expect the incentives to do so to be enormous and the level of confidence we would need in verification to be very high.<br>
我支持提出并讨论这一想法，但我认为它在近期真正实现的可能性不大：如果一方通过逃避监控而退出这类协议，可能会彻底改变全球力量平衡，因此，我预计各方违反协议的诱因会非常强，而我们对验证机制所需要的信心也必须非常高。

Any cooperation we are able to achieve with China will extend the amount of time we have to spend on pacing the frontier within the democratic nations.<br>
我们只要能够与中国实现一定程度的合作，就能延长民主国家内部用于控制前沿 AI 发展节奏的时间窗口。

We should aim for the higher levels while seeing the lower levels as much more likely and realistic.<br>
我们应该把更高层级作为目标，同时认识到较低层级的协议更有可能、更现实。

Finally, it is important to note that even if we cannot achieve formal agreements, simply changing informal norms may have some value.<br>
最后，需要指出的是，即使我们无法达成正式协议，仅仅改变非正式规范，也可能具有一定价值。

Sharing information about recursive self-improvement and about the misalignment of models can help to convince everyone that it is not in their interest to be reckless.<br>
共享有关递归式自我改进以及模型错位的信息，可以帮助各方认识到，鲁莽行事并不符合任何人的利益。

Bottom Line

核心结论

I continue to believe that AI can enormously improve the quality of human life.<br>
我仍然相信，AI 可以极大地提升人类生活的质量。

My desire to achieve these benefits is undimmed.<br>
我希望实现这些益处的愿望从未减弱。

But the benefits will only be achieved if we build the technology in the right way, and — so long as we use the time we gain well — it is worth taking unusually deliberate care to get it right.<br>
但只有以正确的方式发展这项技术，我们才能真正获得这些益处；只要我们能够好好利用争取到的时间，那么值得用一种格外审慎、格外认真负责的方式把事情做好。

Progress will still be relatively fast, and we can use this time to advance the science of interpretability, improve operational security and rigor at the frontier AI companies, and build models whose alignment we have much more confidence in.<br>
发展的速度依然会相对较快，而我们可以利用这段时间推进可解释性科学、提升前沿 AI 公司的运营安全与严谨程度，并构建那些让我们对其对齐程度更有信心的模型。

The measures I propose to advance the frontier at a safe pace will not be easy.<br>
我提出的这些旨在以安全速度推动前沿发展的措施并不容易。

But I believe we owe it to humanity to try.<br>
但我相信，为了人类，我们有责任去尝试。
