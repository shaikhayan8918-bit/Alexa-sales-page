# Alexa-sales-page
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Visibility Code Mentorship</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap');
        body {
            font-family: 'Inter', sans-serif;
            color: #d1d5db; /* Light gray for text */
            background-color: #111827; /* Dark charcoal background */
        }
        .hero-bg {
            background-image: linear-gradient(to bottom, rgba(17, 24, 39, 0.9), rgba(17, 24, 39, 0.9)), url('https://placehold.co/1920x1080/0d131f/c4b5fd?text=YOUR+BACKGROUND+IMAGE');
            background-size: cover;
            background-position: center;
        }
        .gradient-text {
            background-image: linear-gradient(90deg, #a78bfa, #c4b5fd);
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
        }
        .cta-button {
            background: linear-gradient(90deg, #a78bfa, #8b5cf6);
            transition: all 0.3s ease;
            box-shadow: 0 4px 14px 0 rgba(139, 92, 246, 0.39);
        }
        .cta-button:hover {
            transform: translateY(-2px);
            box-shadow: 0 6px 20px 0 rgba(139, 92, 246, 0.5);
        }
        .card {
            background-color: #1f2937; /* Darker gray background for sections */
            border-radius: 1rem;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        .faq-question {
            cursor: pointer;
        }
        .faq-answer {
            max-height: 0;
            overflow: hidden;
            transition: max-height 0.3s ease-in-out;
        }
        .faq-answer.open {
            max-height: 200px; /* Adjust height based on content */
        }
        .video-placeholder {
            width: 100%;
            padding-bottom: 56.25%; /* 16:9 Aspect Ratio */
            position: relative;
        }
        .video-placeholder iframe {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            border-radius: 1rem;
        }
    </style>
</head>
<body class="bg-gray-900 text-gray-300">

    <!-- Hero Section -->
    <header class="hero-bg py-20 px-4 sm:px-6 lg:px-8 text-center rounded-b-[4rem] mb-20">
        <div class="max-w-4xl mx-auto">
            <h1 class="text-4xl sm:text-5xl lg:text-6xl font-bold mb-4 gradient-text">
                FOR AMBITIOUS CREATORS WHO REFUSE TO STAY INVISIBLE
            </h1>
            <p class="text-xl sm:text-2xl lg:text-3xl font-medium mb-8 text-gray-200">
                Go From YouTube Nobody to Client Magnet in 6 Months (Without Burning Out or Chasing Algorithm "Hacks")
            </p>
            <p class="text-lg sm:text-xl text-gray-400 max-w-2xl mx-auto mb-10">
                Stop wasting years posting content that nobody sees... while your expertise sits buried and your bank account stays the same.
            </p>
            
            <!-- VSL Section -->
            <div class="video-placeholder bg-gray-800 rounded-2xl mb-12 shadow-2xl">
                <!-- Replace with your actual video embed code (e.g., YouTube iframe) -->
                <iframe src="https://www.youtube.com/embed/dQw4w9WgXcQ" title="VSL Placeholder" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen class="rounded-2xl"></iframe>
            </div>

            <a href="#application" class="inline-block cta-button text-white text-lg sm:text-xl font-bold py-4 px-8 rounded-full shadow-lg hover:shadow-xl transition-transform transform">
                APPLY FOR MENTORSHIP - LIMITED SPOTS AVAILABLE
            </a>
        </div>
    </header>

    <!-- The Brutal Truth Section -->
    <section class="py-20 px-4 sm:px-6 lg:px-8 text-center">
        <div class="max-w-4xl mx-auto">
            <h2 class="text-3xl sm:text-4xl font-bold mb-6 text-gray-100">
                The Brutal Truth About Why Your YouTube Channel Isn't Working
            </h2>
            <p class="text-lg sm:text-xl text-gray-400 mb-4">
                You're creating content week after week.
                You're following every "guru" strategy you can find.
                You're optimizing titles, thumbnails, and descriptions until your eyes bleed.
            </p>
            <p class="text-lg sm:text-xl text-gray-400 mb-8">
                But your subscriber count is stuck.
                Your views feel like they're coming from your mom and three bots.
                And worst of all? You're starting to wonder if you're just... not cut out for this.
            </p>
            <p class="text-xl sm:text-2xl font-semibold text-gray-200 mb-4">
                Here's what nobody tells you: <span class="gradient-text font-bold">It's not your fault.</span>
            </p>
            <p class="text-lg sm:text-xl text-gray-400 mb-8">
                The YouTube "experts" are feeding you recycled advice from 2019. They're obsessed with vanity metrics that don't pay your bills. They promise overnight success while you're drowning in conflicting strategies that lead absolutely nowhere.
            </p>
            <p class="text-lg sm:text-xl text-gray-400">
                Meanwhile, you're burning out trying to be everything to everyone instead of building a channel that actually attracts your IDEAL clients.
            </p>
            <p class="text-xl sm:text-2xl font-semibold mt-4 text-gray-200">
                Sound familiar?
            </p>
        </div>
    </section>

    <!-- How a Mom of Three Cracked the Code Section -->
    <section class="py-20 px-4 sm:px-6 lg:px-8 bg-gray-800 rounded-3xl mx-4 sm:mx-8 lg:mx-20">
        <div class="max-w-4xl mx-auto text-center">
            <h2 class="text-3xl sm:text-4xl font-bold mb-6 text-gray-100">
                How a Mom of Three Cracked the Code to YouTube Freedom (And Why Everything You've Been Taught is Wrong)
            </h2>
            <p class="text-lg sm:text-xl text-gray-400 mb-4">
                Three years ago, I was exactly where you are now.
                Posting videos into the void.
                Feeling invisible despite putting my heart into every piece of content.
                Watching other creators explode while I struggled to break triple digits on my views.
            </p>
            <p class="text-lg sm:text-xl text-gray-400 mb-4">
                I had the expertise. I had the passion. But I was missing the <span class="font-bold text-white">ONE</span> thing that separates successful YouTube creators from the millions who quit...
            </p>
            <p class="text-xl sm:text-2xl font-semibold mb-8 text-gray-200">
                A system that builds <span class="gradient-text font-bold">BUSINESS</span>, not just an audience.
            </p>
            <p class="text-lg sm:text-xl text-gray-400 mb-4">
                Most creators think YouTube success means millions of subscribers and viral videos.
            </p>
            <p class="text-xl sm:text-2xl font-bold text-gray-200 mb-8">
                Wrong.
            </p>
            <p class="text-lg sm:text-xl text-gray-400 mb-4">
                Real YouTube success means having <span class="font-bold text-white">10,000 engaged subscribers</span> who can't wait to buy from you... rather than 100,000 random people who scroll past your content without a second thought.
            </p>
            <p class="text-lg sm:text-xl text-gray-400 mb-8">
                That's when I discovered what I now call the <span class="gradient-text font-bold">4-Phase Visibility Framework.</span>
            </p>
            <p class="text-lg sm:text-xl text-gray-400 mb-4">
                Not some flashy "secret" or algorithm hack.
            </p>
            <p class="text-lg sm:text-xl text-gray-400 mb-8">
                Just a proven system that turns your expertise into magnetic content... content that doesn't just get views, but gets <span class="font-bold text-white">CLIENTS.</span>
            </p>
            <p class="text-xl sm:text-2xl font-bold text-gray-200 mb-4">
                The result?
            </p>
            <p class="text-lg sm:text-xl text-gray-400 mb-8">
                Six months later, my channel became a client-generating machine. I was booked solid with dream clients who found me through YouTube. And I was finally making the income I deserved from my expertise.
            </p>
            <p class="text-lg sm:text-xl text-gray-400">
                All without burning out, chasing trends, or begging the algorithm for scraps.
            </p>
        </div>
    </section>

    <!-- 4-Phase System Section -->
    <section class="py-20 px-4 sm:px-6 lg:px-8 text-center">
        <div class="max-w-6xl mx-auto">
            <h2 class="text-3xl sm:text-4xl font-bold mb-12 text-gray-100">
                The 4-Phase System That Transforms Invisible Creators Into Client Magnets
            </h2>
            <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-8">
                <div class="card p-8 text-left transition-transform transform hover:scale-105">
                    <div class="text-4xl font-bold text-purple-400 mb-4">01</div>
                    <h3 class="text-xl font-bold text-gray-100 mb-2">Phase 1: The Foundation Reset</h3>
                    <p class="text-gray-400">Stop trying to be everything to everyone. We'll laser-focus your niche and brand so you attract the RIGHT people (the ones with credit cards ready).</p>
                </div>
                <div class="card p-8 text-left transition-transform transform hover:scale-105">
                    <div class="text-4xl font-bold text-purple-400 mb-4">02</div>
                    <h3 class="text-xl font-bold text-gray-100 mb-2">Phase 2: Content That Converts</h3>
                    <p class="text-gray-400">Forget vanity metrics. Learn how to create videos that position you as THE expert your ideal clients have been searching for.</p>
                </div>
                <div class="card p-8 text-left transition-transform transform hover:scale-105">
                    <div class="text-4xl font-bold text-purple-400 mb-4">03</div>
                    <h3 class="text-xl font-bold text-gray-100 mb-2">Phase 3: The Client Pipeline</h3>
                    <p class="text-gray-400">Transform viewers into subscribers, subscribers into leads, and leads into paying clients with a system that works while you sleep.</p>
                </div>
                <div class="card p-8 text-left transition-transform transform hover:scale-105">
                    <div class="text-4xl font-bold text-purple-400 mb-4">04</div>
                    <h3 class="text-xl font-bold text-gray-100 mb-2">Phase 4: Scale Without Stress</h3>
                    <p class="text-gray-400">Build advanced offers and partnerships that multiply your income without multiplying your workload.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Introducing Mentorship Section -->
    <section class="py-20 px-4 sm:px-6 lg:px-8 bg-gray-800 rounded-3xl mx-4 sm:mx-8 lg:mx-20">
        <div class="max-w-4xl mx-auto text-center">
            <h2 class="text-3xl sm:text-4xl font-bold mb-6 text-gray-100">
                Introducing: The Visibility Code Mentorship
            </h2>
            <p class="text-lg sm:text-xl text-gray-400 mb-8">
                6 months of intensive, personalized mentorship to transform your YouTube channel from a time-wasting hobby into a client-generating business.
            </p>
            <div class="card p-8 text-left">
                <h3 class="text-2xl font-bold text-gray-100 mb-4">Here's what you get:</h3>
                <ul class="space-y-4 text-lg text-gray-300">
                    <li class="flex items-start">
                        <span class="text-purple-400 text-xl font-bold mr-3">&check;</span>
                        <div>
                            <span class="font-bold text-gray-100">Bi-weekly 1:1 Strategy Calls</span>
                            <br/> Direct access to work through your specific challenges and opportunities
                        </div>
                    </li>
                    <li class="flex items-start">
                        <span class="text-purple-400 text-xl font-bold mr-3">&check;</span>
                        <div>
                            <span class="font-bold text-gray-100">Complete Channel Audit</span>
                            <br/> I'll personally review your channel and give you the exact roadmap to fix what's broken
                        </div>
                    </li>
                    <li class="flex items-start">
                        <span class="text-purple-400 text-xl font-bold mr-3">&check;</span>
                        <div>
                            <span class="font-bold text-gray-100">The YouTube Freedom Formula Course</span>
                            <br/> Self-paced modules you can access 24/7 to implement at your own speed
                        </div>
                    </li>
                    <li class="flex items-start">
                        <span class="text-purple-400 text-xl font-bold mr-3">&check;</span>
                        <div>
                            <span class="font-bold text-gray-100">Direct Message Support</span>
                            <br/> Stuck on something? Need quick feedback? Message me directly for immediate guidance
                        </div>
                    </li>
                    <li class="flex items-start">
                        <span class="text-purple-400 text-xl font-bold mr-3">&check;</span>
                        <div>
                            <span class="font-bold text-gray-100">Done-For-You Templates & Systems</span>
                            <br/> The exact templates I use for titles, thumbnails, and content planning
                        </div>
                    </li>
                    <li class="flex items-start">
                        <span class="text-purple-400 text-xl font-bold mr-3">&check;</span>
                        <div>
                            <span class="font-bold text-gray-100">Monetization Blueprint</span>
                            <br/> Step-by-step instructions for turning your audience into paying clients
                        </div>
                    </li>
                </ul>
            </div>
            <p class="text-xl sm:text-2xl font-bold mt-8 text-gray-200">
                This isn't for hobbyists or tire-kickers.
            </p>
            <p class="text-lg sm:text-xl text-gray-400 mt-4">
                This is for serious creators who are ready to invest in building a real business around their expertise.
            </p>
        </div>
    </section>

    <!-- Who This Is For Section -->
    <section class="py-20 px-4 sm:px-6 lg:px-8 text-center">
        <div class="max-w-4xl mx-auto">
            <h2 class="text-3xl sm:text-4xl font-bold mb-8 text-gray-100">
                Who This Is For (And Who It's NOT For)
            </h2>
            <div class="grid md:grid-cols-2 gap-8 text-left">
                <div class="card p-8">
                    <h3 class="text-2xl font-bold text-gray-100 mb-4">This IS for you if:</h3>
                    <ul class="space-y-2 text-lg text-gray-300 list-disc list-inside">
                        <li>You're a coach, consultant, educator, or expert who wants to use YouTube to attract premium clients</li>
                        <li>You're willing to invest 6 months in building something that lasts</li>
                        <li>You're tired of random advice and want a personalized strategy</li>
                        <li>You value freedom and balance over hustle and burnout</li>
                    </ul>
                </div>
                <div class="card p-8">
                    <h3 class="text-2xl font-bold text-gray-100 mb-4">This is NOT for you if:</h3>
                    <ul class="space-y-2 text-lg text-gray-300 list-disc list-inside">
                        <li>You're looking for get-rich-quick schemes or overnight success</li>
                        <li>You want to be the next MrBeast (this is about business, not entertainment)</li>
                        <li>You're not willing to invest time and money in your growth</li>
                        <li>You just want more subscribers without caring about revenue</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- How to Get Started Section -->
    <section id="application" class="py-20 px-4 sm:px-6 lg:px-8 bg-gray-800 rounded-3xl mx-4 sm:mx-8 lg:mx-20">
        <div class="max-w-4xl mx-auto text-center">
            <h2 class="text-3xl sm:text-4xl font-bold mb-6 text-gray-100">
                Here's How to Get Started
            </h2>
            <p class="text-lg sm:text-xl text-gray-400 mb-8">
                Spots are limited because this is intensive, personalized mentorship.
                I only work with creators who are serious about transformation.
            </p>
            <div class="grid md:grid-cols-3 gap-8 text-left mb-10">
                <div class="card p-6 flex flex-col items-center">
                    <div class="text-4xl font-bold text-purple-400 mb-2">1</div>
                    <p class="text-lg text-gray-300 text-center">Click the button below to fill out your application</p>
                </div>
                <div class="card p-6 flex flex-col items-center">
                    <div class="text-4xl font-bold text-purple-400 mb-2">2</div>
                    <p class="text-lg text-gray-300 text-center">If you're a good fit, we'll schedule a strategy call</p>
                </div>
                <div class="card p-6 flex flex-col items-center">
                    <div class="text-4xl font-bold text-purple-400 mb-2">3</div>
                    <p class="text-lg text-gray-300 text-center">We'll discuss your goals and see if we're aligned to work together</p>
                </div>
            </div>
            <p class="text-lg sm:text-xl text-gray-400 mb-8">
                No pushy sales tactics. No pressure. Just an honest conversation about whether this mentorship can help you achieve your goals.
            </p>
            <a href="#" class="inline-block cta-button text-white text-lg sm:text-xl font-bold py-4 px-8 rounded-full shadow-lg hover:shadow-xl transition-transform transform">
                APPLY FOR MENTORSHIP NOW
            </a>
        </div>
    </section>

    <!-- FAQ Section -->
    <section class="py-20 px-4 sm:px-6 lg:px-8">
        <div class="max-w-4xl mx-auto">
            <h2 class="text-3xl sm:text-4xl font-bold mb-8 text-center text-gray-100">
                Frequently Asked Questions
            </h2>
            <div class="space-y-6">
                <div class="card p-6">
                    <div class="flex justify-between items-center faq-question" onclick="toggleFaq(this)">
                        <h3 class="text-xl font-semibold text-gray-100">Q: How much does the mentorship cost?</h3>
                        <span class="text-2xl font-bold text-purple-400">+</span>
                    </div>
                    <div class="faq-answer mt-4 text-lg text-gray-400">
                        <p>A: Investment details are shared during our strategy call after your application is reviewed. This ensures we're a good fit before discussing numbers.</p>
                    </div>
                </div>
                <div class="card p-6">
                    <div class="flex justify-between items-center faq-question" onclick="toggleFaq(this)">
                        <h3 class="text-xl font-semibold text-gray-100">Q: What if I don't have time to implement everything?</h3>
                        <span class="text-2xl font-bold text-purple-400">+</span>
                    </div>
                    <div class="faq-answer mt-4 text-lg text-gray-400">
                        <p>A: This program is designed for busy creators. We'll work with your schedule and prioritize the actions that move the needle most.</p>
                    </div>
                </div>
                <div class="card p-6">
                    <div class="flex justify-between items-center faq-question" onclick="toggleFaq(this)">
                        <h3 class="text-xl font-semibold text-gray-100">Q: How is this different from other YouTube courses?</h3>
                        <span class="text-2xl font-bold text-purple-400">+</span>
                    </div>
                    <div class="faq-answer mt-4 text-lg text-gray-400">
                        <p>A: Most courses give you generic strategies. This is personalized mentorship where we build YOUR specific path to success together.</p>
                    </div>
                </div>
                <div class="card p-6">
                    <div class="flex justify-between items-center faq-question" onclick="toggleFaq(this)">
                        <h3 class="text-xl font-semibold text-gray-100">Q: What if YouTube changes their algorithm?</h3>
                        <span class="text-2xl font-bold text-purple-400">+</span>
                    </div>
                    <div class="faq-answer mt-4 text-lg text-gray-400">
                        <p>A: Algorithm changes don't matter when you have a business-focused strategy. We build foundations that last regardless of platform updates.</p>
                    </div>
                </div>
                <div class="card p-6">
                    <div class="flex justify-between items-center faq-question" onclick="toggleFaq(this)">
                        <h3 class="text-xl font-semibold text-gray-100">Q: Do you guarantee results?</h3>
                        <span class="text-2xl font-bold text-purple-400">+</span>
                    </div>
                    <div class="faq-answer mt-4 text-lg text-gray-400">
                        <p>A: I can't guarantee your results because success depends on implementation. But I guarantee you'll have a clear, personalized roadmap and my full support to achieve your goals.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Final CTA Section -->
    <section class="py-20 px-4 sm:px-6 lg:px-8 text-center bg-gray-900 rounded-t-[4rem]">
        <div class="max-w-4xl mx-auto">
            <h2 class="text-3xl sm:text-4xl font-bold mb-6 text-gray-100">
                Ready to stop being YouTube's best-kept secret?
            </h2>
            <p class="text-lg sm:text-xl text-gray-400 mb-4">
                The creators who succeed on YouTube aren't the most talented or the luckiest.
            </p>
            <p class="text-lg sm:text-xl text-gray-400 mb-8">
                They're the ones who get the right guidance and take action.
            </p>
            <p class="text-xl sm:text-2xl font-semibold text-gray-200 mb-8">
                Your expertise deserves to be seen. Your message deserves to reach the people who need it most.
            </p>
            <p class="text-lg sm:text-xl text-gray-400 mb-10">
                Stop letting another month pass by hoping things will magically change.
            </p>
            <a href="#application" class="inline-block cta-button text-white text-lg sm:text-xl font-bold py-4 px-8 rounded-full shadow-lg hover:shadow-xl transition-transform transform">
                APPLY FOR THE VISIBILITY CODE MENTORSHIP
            </a>
            <p class="text-sm text-gray-500 mt-4">
                Limited spots available. Applications reviewed within 48 hours.
            </p>
        </div>
    </section>

    <script>
        // JavaScript for FAQ accordion functionality
        function toggleFaq(element) {
            const answer = element.nextElementSibling;
            const plusSign = element.querySelector('span');

            if (answer.classList.contains('open')) {
                answer.classList.remove('open');
                plusSign.textContent = '+';
            } else {
                answer.classList.add('open');
                plusSign.textContent = '-';
            }
        }
    </script>
</body>
</html>
