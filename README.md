<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Christopher Odhiambo | Teacher of English & Literature</title>
    <style>
        /* =========================================================
           CLASSIC HUMAN ACADEMIC & TEACHING PORTFOLIO STYLESHEET
           Font: Times New Roman | Palette: Warm Cream, Ink, Maroon, Navy
           ========================================================= */
        :root {
            --paper-bg: #f9f6f0;
            --card-bg: #ffffff;
            --ink-main: #1c1c1c;
            --ink-muted: #4a4a4a;
            --navy: #14284b;
            --maroon: #6e1a24;
            --gold-border: #c5b38a;
            --rule-line: #dcd6c8;
            --chalkboard: #1d3528;
            --chalk-text: #f4f1ea;
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            font-family: "Times New Roman", Times, Georgia, serif;
            background-color: var(--paper-bg);
            color: var(--ink-main);
            line-height: 1.65;
            font-size: 18px;
        }

        /* Top Navigation Bar */
        header {
            background-color: var(--navy);
            color: #ffffff;
            border-bottom: 4px solid var(--maroon);
            position: sticky;
            top: 0;
            z-index: 100;
        }

        .nav-container {
            max-width: 1080px;
            margin: 0 auto;
            padding: 14px 20px;
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
            align-items: center;
            gap: 15px;
        }

        .site-title {
            font-size: 1.35rem;
            font-weight: bold;
            letter-spacing: 0.5px;
            color: #ffffff;
            text-decoration: none;
        }

        nav a {
            color: #e6e1d6;
            text-decoration: none;
            margin-left: 20px;
            font-size: 1rem;
            padding-bottom: 3px;
            border-bottom: 2px solid transparent;
        }

        nav a:hover {
            color: #ffffff;
            border-bottom: 2px solid var(--gold-border);
        }

        /* Main Container */
        .container {
            max-width: 1080px;
            margin: 0 auto;
            padding: 35px 20px;
        }

        section {
            margin-bottom: 55px;
            padding-bottom: 40px;
            border-bottom: 1px solid var(--rule-line);
        }

        h1, h2, h3, h4 {
            color: var(--navy);
            font-weight: bold;
            line-height: 1.25;
        }

        h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
        }

        h2 {
            font-size: 1.85rem;
            margin-bottom: 20px;
            padding-bottom: 8px;
            border-bottom: 2px solid var(--maroon);
            display: inline-block;
        }

        h3 {
            font-size: 1.35rem;
            margin-bottom: 8px;
            color: var(--maroon);
        }

        p {
            margin-bottom: 14px;
        }

        /* Hero / Introduction Grid */
        .hero-grid {
            display: grid;
            grid-template-columns: 260px 1fr;
            gap: 35px;
            align-items: start;
            background: var(--card-bg);
            padding: 30px;
            border: 1px solid var(--gold-border);
            box-shadow: 0 3px 10px rgba(0,0,0,0.05);
        }

        /* Photo Placeholder Styling */
        .photo-frame {
            border: 2px dashed var(--gold-border);
            background-color: #f3efe6;
            padding: 10px;
            text-align: center;
        }

        .photo-frame img {
            width: 100%;
            height: auto;
            display: block;
            border: 1px solid #ccc;
            background-color: #e5dfd2;
            min-height: 270px;
            object-fit: cover;
        }

        .photo-caption {
            font-size: 0.85rem;
            font-style: italic;
            color: var(--ink-muted);
            margin-top: 8px;
        }

        .contact-bar {
            margin-top: 18px;
            padding-top: 14px;
            border-top: 1px solid var(--rule-line);
            font-size: 0.95rem;
            display: flex;
            flex-wrap: wrap;
            gap: 18px;
        }

        .contact-bar a {
            color: var(--maroon);
            text-decoration: none;
            font-weight: bold;
        }

        /* Gallery Grid for Classroom Photos */
        .gallery-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(230px, 1fr));
            gap: 20px;
            margin-top: 15px;
        }

        .gallery-box {
            background: var(--card-bg);
            border: 1px solid var(--rule-line);
            padding: 12px;
        }

        .gallery-img-slot {
            width: 100%;
            height: 170px;
            background-color: #ebe5d8;
            border: 1px dashed #8c7f65;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            padding: 15px;
            font-size: 0.9rem;
            color: #5a5243;
            object-fit: cover;
        }

        /* Pedagogical Tabs */
        .folder-tabs {
            display: flex;
            flex-wrap: wrap;
            gap: 8px;
            margin-bottom: -1px;
        }

        .tab-btn {
            font-family: "Times New Roman", Times, serif;
            font-size: 1.05rem;
            padding: 10px 20px;
            background-color: #e8e2d5;
            border: 1px solid var(--gold-border);
            border-bottom: none;
            cursor: pointer;
            color: var(--ink-main);
        }

        .tab-btn.active {
            background-color: var(--card-bg);
            font-weight: bold;
            color: var(--maroon);
            border-top: 3px solid var(--maroon);
        }

        .paper-sheet {
            background-color: var(--card-bg);
            border: 1px solid var(--gold-border);
            padding: 32px;
            box-shadow: 0 4px 12px rgba(0,0,0,0.04);
        }

        /* Tables for Lesson Plans & Schemes */
        table {
            width: 100%;
            border-collapse: collapse;
            margin: 18px 0;
            font-size: 0.95rem;
        }

        th, td {
            border: 1px solid #8c8577;
            padding: 10px 12px;
            vertical-align: top;
            text-align: left;
        }

        th {
            background-color: #efeae0;
            color: var(--navy);
            font-weight: bold;
        }

        /* Chalkboard Simulation Box */
        .chalkboard {
            background-color: var(--chalkboard);
            color: var(--chalk-text);
            border: 8px solid #6b4c35;
            padding: 22px;
            margin: 20px 0;
            font-family: "Times New Roman", serif;
        }

        .chalkboard h4 {
            color: #f4d06f;
            border-bottom: 1px dashed #a3b899;
            padding-bottom: 6px;
            margin-bottom: 12px;
            text-transform: uppercase;
            letter-spacing: 1px;
        }

        /* Exam Paper Specifics */
        .exam-header {
            text-align: center;
            border-bottom: 2px double var(--ink-main);
            padding-bottom: 15px;
            margin-bottom: 22px;
        }

        .answer-line {
            border-bottom: 1px dotted #777;
            height: 26px;
            margin-bottom: 8px;
        }

        .marking-scheme-box {
            display: none;
            background-color: #f2f7f4;
            border-left: 4px solid #1d6f42;
            padding: 15px 20px;
            margin-top: 15px;
            font-size: 0.95rem;
        }

        .btn-action {
            font-family: "Times New Roman", Times, serif;
            font-size: 1rem;
            background-color: var(--navy);
            color: #ffffff;
            border: 1px solid var(--navy);
            padding: 8px 18px;
            cursor: pointer;
            margin-top: 10px;
            display: inline-block;
            text-decoration: none;
        }

        .btn-action:hover {
            background-color: var(--maroon);
            border-color: var(--maroon);
        }

        /* Two-Column CV Grid */
        .two-col {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 28px;
        }

        .cv-entry {
            background: var(--card-bg);
            border: 1px solid var(--rule-line);
            padding: 20px;
            margin-bottom: 18px;
        }

        .cv-date {
            font-style: italic;
            color: var(--maroon);
            font-size: 0.95rem;
            float: right;
        }

        ul.classic-list {
            margin-left: 22px;
            margin-top: 8px;
        }

        ul.classic-list li {
            margin-bottom: 6px;
        }

        @media (max-width: 768px) {
            .hero-grid, .two-col {
                grid-template-columns: 1fr;
            }
            .cv-date {
                float: none;
                display: block;
            }
        }

        @media print {
            header, .folder-tabs, .btn-action {
                display: none;
            }
            body {
                background: #fff;
            }
        }
    </style>
</head>
<body>

    <!-- Top Navigation -->
    <header>
        <div class="nav-container">
            <a href="#" class="site-title">CHRISTOPHER ODHIAMBO</a>
            <nav>
                <a href="#about">About Me</a>
                <a href="#classroom-work">Lesson Plans & Exams</a>
                <a href="#experience">Teaching History</a>
                <a href="#research">Linguistics Research</a>
                <a href="#gallery">Photo Gallery</a>
                <a href="#referees">Referees</a>
            </nav>
        </div>
    </header>

    <div class="container">

        <!-- 1. HERO & PERSONAL INTRODUCTION -->
        <section id="about">
            <div class="hero-grid">
                <!-- Left: Teacher Portrait Slot -->
                <div class="photo-frame">
                    <!-- REPLACE 'my-profile-photo.jpg' WITH YOUR ACTUAL PHOTO FILE NAME -->
                    <img src="my-profile-photo.jpg" alt="Paste your passport or classroom portrait here (my-profile-photo.jpg)" onerror="this.style.display='none'; this.nextElementSibling.style.display='flex';">
                    <div class="gallery-img-slot" style="display:none; height:270px;">
                        [Insert Your Portrait Here]<br><br>Save your photo as <strong>my-profile-photo.jpg</strong> in the same folder.
                    </div>
                    <div class="photo-caption">
                        Christopher Odhiambo<br>B.Ed. (Arts), M.A. Candidate (MMUST)
                    </div>
                </div>

                <!-- Right: Human-Written Bio -->
                <div>
                    <h1>Christopher Odhiambo</h1>
                    <h3 style="margin-bottom: 16px;">Teacher of English, Literature & Pre-Technical Studies | Applied Linguistics Researcher</h3>
                    
                    <p>
                        I am a classroom teacher and postgraduate linguist with over three years of practical teaching experience across Kenyan secondary schools and international school curricula. Having taught under both the <strong>Competency-Based Curriculum (CBC)</strong> at the Junior and Senior School levels and the <strong>Cambridge IGCSE</strong> system, my daily work revolves around helping learners read closely, argue clearly on paper, and speak with confidence.
                    </p>
                    <p>
                        Alongside classroom teaching, I am completing my Master of Arts in Applied Linguistics at <strong>Masinde Muliro University of Science and Technology (MMUST)</strong>. My thesis examines <em>The Role of Social Deixis in Pragmatic Enrichment of Dholuo Polysemous Expressions</em>—studying how everyday speakers use social relationships, kinship, and context to give single words multiple rich meanings. I bring this same love for how language works in real life into my literature, grammar, and ESL lessons.
                    </p>
                    <p>
                        Outside school hours, I run <strong>The Novel Zone</strong> (a community book club founded in 2021) and experiment with Python and data tools to track how students improve their writing over a school term.
                    </p>

                    <div class="contact-bar">
                        <span><strong>Location:</strong> Nairobi / Kakamega / Homa Bay, Kenya</span>
                        <span><strong>Phone:</strong> <a href="tel:+254797775403">+254 797 775 403</a></span>
                        <span><strong>Email:</strong> <a href="mailto:odhiambochris99@gmail.com">odhiambochris99@gmail.com</a></span>
                        <span><strong>LinkedIn:</strong> <a href="https://linkedin.com/in/christopher-samwel-8816252a3" target="_blank">christopher-samwel</a></span>
                    </div>
                </div>
            </div>
        </section>

        <!-- 2. INTERACTIVE CLASSROOM WORK: REAL LESSON PLAN, REAL EXAM PAPER, REAL ESL NOTES -->
        <section id="classroom-work">
            <h2>Inside My Classroom: Real Lesson Plans & Exam Papers</h2>
            <p>
                Click the tabs below to inspect actual teaching records from my classes: a 40-minute Senior Secondary Literature lesson plan, a Grade 8 CBC English & Oral Literature test paper with a toggleable marking scheme, and my one-on-one ESL teaching notes from Mahanaim International School.
            </p>

            <!-- Folder Tabs -->
            <div class="folder-tabs">
                <button class="tab-btn active" onclick="openDocTab('doc-lesson', this)">1. Form 3 / Senior School Lesson Plan</button>
                <button class="tab-btn" onclick="openDocTab('doc-exam', this)">2. Grade 8 CBC Exam Paper & Marking Scheme</button>
                <button class="tab-btn" onclick="openDocTab('doc-esl', this)">3. IGCSE & Chinese-ESL Tutoring Notes</button>
                <button class="tab-btn" onclick="openDocTab('doc-marker', this)">4. Interactive Essay Paragraph Marker</button>
            </div>

            <!-- TAB 1: REAL 40-MINUTE LESSON PLAN -->
            <div id="doc-lesson" class="paper-sheet">
                <div class="exam-header">
                    <h3 style="color: var(--navy); margin-bottom: 4px;">STANDARD KENYAN SECONDARY SCHOOL LESSON PLAN</h3>
                    <p style="margin:0; font-size: 0.95rem;"><strong>Teacher:</strong> Mr. Christopher Odhiambo &nbsp;|&nbsp; <strong>Subject:</strong> Literature in English (Set Book Analysis)</p>
                </div>

                <table>
                    <tr>
                        <th>School Level:</th>
                        <td>Senior Secondary (Form 3 / Grade 11)</td>
                        <th>Date / Time:</th>
                        <td>8:00 AM – 8:40 AM (40 Minutes)</td>
                    </tr>
                    <tr>
                        <th>Topic:</th>
                        <td>Intensive Reading: <em>The Samaritan</em> by John Lara</td>
                        <th>Roll:</th>
                        <td>42 Learners Present</td>
                    </tr>
                    <tr>
                        <th>Sub-Topic:</th>
                        <td colspan="3">Satire and Misuse of Public Office in Act 1, Scene 1 (The Launch of "The Samaritan" App)</td>
                    </tr>
                </table>

                <p><strong>Instructional Objectives:</strong> By the end of the 40-minute lesson, the learner should be able to:</p>
                <ol style="margin-left: 25px; margin-bottom: 15px;">
                    <li>Identify instances of situational irony and satire during Mayor Mossi's speech at Sagrada Secondary School.</li>
                    <li>Dramatize the dialogue between Alvita, Montano, and Mayor Mossi with appropriate vocal tone.</li>
                    <li>Write a well-illustrated 8-line paragraph explaining why Mayor Mossi refuses to launch the innovation app.</li>
                </ol>

                <p><strong>Learning References & Resources:</strong></p>
                <ul class="classic-list" style="margin-bottom: 18px;">
                    <li>John Lara, <em>The Samaritan</em> (Pages 1–14).</li>
                    <li>Chalkboard, duster, and learners' Literature exercise books.</li>
                </ul>

                <table>
                    <thead>
                        <tr>
                            <th style="width: 16%;">Stage & Time</th>
                            <th style="width: 42%;">Teacher's Activities (Mr. Odhiambo)</th>
                            <th style="width: 42%;">Learners' Activities & Expected Responses</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td><strong>Introduction</strong><br>(5 Minutes)</td>
                            <td>
                                Greets the class. Writes the word <em>"WHISTLEBLOWER"</em> on the board.<br><br>
                                <strong>Question to Class:</strong> "If you built a mobile phone app that reported every person who stole school loaves of bread, who would be the first person to ban that app?"
                            </td>
                            <td>
                                Learners raise hands and respond:<br>
                                <em>Expected answer:</em> "The prefects or the person stealing the bread!"<br>
                                Learners connect the hook to Mayor Mossi's fear of <em>The Samaritan</em> app.
                            </td>
                        </tr>
                        <tr>
                            <td><strong>Lesson Development: Step 1 (Role-Play)</strong><br>(12 Minutes)</td>
                            <td>
                                Selects three learners to come to the front and read aloud the parts of <strong>Alvita</strong>, <strong>Montano</strong>, and <strong>Mayor Mossi</strong> (Act 1, Scene 1, pp. 8–11).<br>
                                Stops the reading at page 10 to ask why Mossi’s tone suddenly shifts from praising the students to making excuses.
                            </td>
                            <td>
                                Selected learners dramatize the scene with appropriate facial expressions.<br>
                                Rest of the class follows in their set books and points out the stage direction: <em>(Scratching his head nervously)</em>.
                            </td>
                        </tr>
                        <tr>
                            <td><strong>Step 2 (Close Text Analysis)</strong><br>(13 Minutes)</td>
                            <td>
                                Guides learners in pairs to define <strong>Satire</strong> using Mossi's excuse that the app might be used for "political witch-hunts."<br>
                                Writes the two guiding columns on the chalkboard: <em>What Mayor Mossi Says vs. What Mayor Mossi Really Fears.</em>
                            </td>
                            <td>
                                In pairs, learners find direct quotes from pages 11–13 and dictate them to the teacher to fill in the chalkboard table.
                            </td>
                        </tr>
                        <tr>
                            <td><strong>Conclusion & Evaluation</strong><br>(10 Minutes)</td>
                            <td>
                                Instructs learners to write one complete PEEE paragraph (Point, Evidence, Explanation, Evaluation) answering: <em>"How does Lara use the school prize-giving day to expose municipal corruption?"</em><br>
                                Walks around the rows marking the first five completed books.
                            </td>
                            <td>
                                Learners copy the chalkboard summary and write their analytical paragraph in their exercise books.
                            </td>
                        </tr>
                    </tbody>
                </table>

                <!-- Realistic Chalkboard Summary -->
                <div class="chalkboard">
                    <h4>CHALKBOARD SUMMARY (BOARD LAYOUT — FORM 3 EAST)</h4>
                    <p><strong>DATE:</strong> 18th October 2026 &nbsp;&nbsp;|&nbsp;&nbsp; <strong>SUBJECT:</strong> LITERATURE IN ENGLISH</p>
                    <p><strong>TOPIC:</strong> SATIRE IN JOHN LARA'S <em>THE SAMARITAN</em> (ACT 1, SCENE 1)</p>
                    <hr style="border: 0.5px dashed #88a090; margin: 10px 0;">
                    <p>1. <strong>Satire:</strong> Using humour, irony, or exaggeration to criticize human folly and corruption in society.</p>
                    <p>2. <strong>Dramatic Irony at Sagrada Secondary School:</strong></p>
                    <p style="margin-left: 20px;">• The students (Alvita & Montano) expect Mayor Mossi to reward their digital app because it promotes transparency.</p>
                    <p style="margin-left: 20px;">• Instead, Mossi panics because the app allows citizens to post verified evidence of municipal looting.</p>
                    <p>3. <strong>Assignment for Tomorrow:</strong> Read Act 1, Scene 2 and list three accusations made against Hon. Seymour and Hon. Ted.</p>
                </div>
            </div>

            <!-- TAB 2: REAL GRADE 8 CBC EXAM PAPER -->
            <div id="doc-exam" class="paper-sheet" style="display: none;">
                <div class="exam-header">
                    <h3 style="color: var(--navy); margin-bottom: 2px;">NYASOTI COMPREHENSIVE SCHOOL — MAGUNGA</h3>
                    <p style="margin:0; font-weight: bold;">JUNIOR SCHOOL CONTINUOUS ASSESSMENT TEST (GRADE 8)</p>
                    <p style="margin:0; font-size: 0.95rem;"><strong>LEARNING AREA:</strong> ENGLISH LANGUAGE & ORAL LITERATURE &nbsp;|&nbsp; <strong>TIME:</strong> 1 HOUR 15 MINS</p>
                    <p style="margin-top:6px; font-size: 0.9rem;"><strong>NAME:</strong> ________________________________________ <strong>ADM NO:</strong> __________ <strong>DATE:</strong> ______________</p>
                </div>

                <h4>SECTION A: ORAL LITERATURE (15 MARKS)</h4>
                <p><em>Read the oral narrative below carefully and answer the questions that follow.</em></p>

                <div style="background: #faf7f0; border-left: 3px solid var(--navy); padding: 15px 20px; margin-bottom: 18px; font-style: italic;">
                    Long ago in the village of Sakwa, a terrible drought dried up all the rivers until even the papyrus reeds turned to ash. Hare (Apuoyo) and Hyena (Ototoni) agreed to dig a shared well at the edge of the forest. Every morning when the cock crowed, Hare pretended to groan in pain, tying dry banana leaves around his stomach. "Omera," Hare cried to Hyena, "my belly is twisted like a sisal rope! Go ahead and dig; I will bring the calabashes later."<br><br>
                    Foolish Hyena dug alone under the fierce sun until clear, cool water bubbled from the red earth. Yet every night, when Hyena went home to sleep, Hare crept out with two big clay pots, drank his fill, and washed his dusty paws right inside the clean water! When Hyena discovered small three-toed footprints in the mud the next morning, he carved a sticky wooden figure smeared with wild rubber sap and placed it beside the water...
                </div>

                <p><strong>1.</strong> Classify the oral narrative above and give one reason for your answer. <em>(2 Marks)</em></p>
                <div class="answer-line"></div>
                <div class="answer-line"></div>

                <p><strong>2.</strong> Identify and illustrate <strong>two</strong> features of oral narratives evident in the story above. <em>(4 Marks)</em></p>
                <div class="answer-line"></div>
                <div class="answer-line"></div>

                <p><strong>3.</strong> Why did the storyteller include the Dholuo word <em>"Omera"</em> in Hare's speech? <em>(2 Marks)</em></p>
                <div class="answer-line"></div>

                <p><strong>4.</strong> State one character trait of Hare and one character trait of Hyena based on the passage. <em>(4 Marks)</em></p>
                <div class="answer-line"></div>
                <div class="answer-line"></div>

                <p><strong>5.</strong> If you were performing this story before Grade 8 learners during assembly, how would you say the line: <em>"my belly is twisted like a sisal rope!"</em>? (Give one verbal and one non-verbal cue). <em>(3 Marks)</em></p>
                <div class="answer-line"></div>
                <div class="answer-line"></div>

                <h4 style="margin-top: 25px;">SECTION B: GRAMMAR IN USE (5 MARKS)</h4>
                <p><strong>6.</strong> Rewrite the following sentences according to the instructions given in brackets:</p>
                <p style="margin-left: 15px;">(a) Hyena dug the well alone. He did not complain to the elders. <em>(Begin: Despite...)</em> (1 Mark)</p>
                <div class="answer-line"></div>
                <p style="margin-left: 15px;">(b) "Did you muddy the water last night?" Hyena asked Hare. <em>(Rewrite in reported speech)</em> (2 Marks)</p>
                <div class="answer-line"></div>
                <p style="margin-left: 15px;">(c) Replace the underlined word with the correct phrasal verb: The headteacher <u>postponed</u> the debate club meeting to Friday. <em>(put off / put out / put down)</em> (2 Marks)</p>
                <div class="answer-line"></div>

                <button class="btn-action" onclick="toggleMarkingScheme()">Show / Hide Teacher's Marking Scheme</button>

                <!-- Hidden Teacher Marking Scheme -->
                <div id="marking-scheme" class="marking-scheme-box">
                    <h4 style="color: #1d6f42; margin-bottom: 10px;">TEACHER'S MARKING SCHEME (PREPARED BY MR. C. ODHIAMBO)</h4>
                    <p><strong>1. Classification:</strong> Trickster narrative (1 mk) — Hare uses deceit/cunning (feigning illness) to exploit Hyena's labour without digging the well (1 mk).</p>
                    <p><strong>2. Features of Oral Narratives:</strong><br>
                    • <em>Opening formula:</em> "Long ago in the village of Sakwa..." (2 mks)<br>
                    • <em>Direct speech / Dialogue:</em> "Omera... my belly is twisted..." (2 mks)<br>
                    • <em>Simile:</em> "...twisted like a sisal rope" (Accept any two well-illustrated points).</p>
                    <p><strong>3. Use of "Omera":</strong> Establishes local cultural authenticity/setting and serves as a social deictic marker of false brotherhood/familiarity to soften Hyena's suspicion (2 mks).</p>
                    <p><strong>4. Character Traits:</strong><br>
                    • <em>Hare:</em> Cunning / deceitful / lazy / ungrateful — pretends to be sick and muddies the water (2 mks).<br>
                    • <em>Hyena:</em> Gullible / hardworking (at first) / observant — notices the footprints and sets a trap (2 mks).</p>
                    <p><strong>5. Performance Cues:</strong><br>
                    • <em>Verbal:</em> Speak in a weak, trembling, high-pitched groaning voice (1.5 mks).<br>
                    • <em>Non-verbal:</em> Clutch the stomach with both hands and bend over with a grimacing facial expression (1.5 mks).</p>
                    <p><strong>6. Grammar:</strong><br>
                    (a) Despite digging the well alone, Hyena did not complain to the elders. (1 mk)<br>
                    (b) Hyena asked Hare whether/if he had muddied the water the previous night / the night before. (2 mks)<br>
                    (c) <strong>put off</strong> (2 mks).</p>
                </div>
            </div>

            <!-- TAB 3: IGCSE & ESL TUTORING FIELD NOTES -->
            <div id="doc-esl" class="paper-sheet" style="display: none;">
                <h3>Mahanaim International School — One-on-One ESL & IGCSE Instruction Notes</h3>
                <p>
                    During my tenure at <strong>Mahanaim International School (Kasarani, Nairobi)</strong>, alongside teaching Cambridge IGCSE English Language and Literature, I served as a specialised ESL tutor for two Chinese-speaking learners adapting to an English-medium curriculum.
                </p>

                <h4>How I Solved Real First-Language (Mandarin) Transfer Hurdles in Class</h4>
                <p>
                    Instead of giving generic grammar drills, I used my training in Applied Linguistics to compare how Mandarin and English build sentences differently:
                </p>

                <table>
                    <thead>
                        <tr>
                            <th>Common Student Sentence (Before)</th>
                            <th>Linguistic Root Cause (L1 Transfer)</th>
                            <th>My Classroom Fix & Target Output</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td><em>"Yesterday I go to Nairobi library and borrow book."</em></td>
                            <td>Mandarin does not inflect verbs for past tense; it relies on time adverbs (<em>yesterday</em>) or aspect markers (<em>le</em>) and lacks mandatory indefinite articles (<em>a/an</em>).</td>
                            <td>
                                Built a physical colour-card timeline on the desk. Every time a sentence started with a past time word, the student had to flip the verb card to its red Past Tense side:<br>
                                <strong>"Yesterday I <u>went</u> to <u>the</u> Nairobi library and <u>borrowed</u> <u>a</u> book."</strong>
                            </td>
                        </tr>
                        <tr>
                            <td><em>"Although he was tired, but he finished the homework."</em></td>
                            <td>In Mandarin, concessive clauses require the paired structure <em>Suīrán (Although)... dànshì (but)...</em></td>
                            <td>
                                Taught the "One Bridge Only" rule: English clauses only need one connector bridge.<br>
                                <strong>"Although he was tired, he finished the homework."</strong>
                            </td>
                        </tr>
                    </tbody>
                </table>
            </div>

            <!-- TAB 4: INTERACTIVE ESSAY MARKER -->
            <div id="doc-marker" class="paper-sheet" style="display: none;">
                <h3>Teacher's Interactive Paragraph Checker (Classroom Tool)</h3>
                <p>
                    When marking forty essay books, I train students to check their own paragraphs before handing them in. Paste a student's paragraph below to check its word count, average sentence length, and whether it contains evidence markers (quotes or connectors).
                </p>

                <textarea id="student-paragraph" rows="5" style="width: 100%; font-family: 'Times New Roman', serif; font-size: 1.05rem; padding: 12px; border: 1px solid #8c8577; margin-bottom: 12px;">In Act 1 of The Samaritan, Mayor Mossi is portrayed as a hypocritical leader. For example, when Alvita and Montano present their innovation, he praises them in public, however he secretly refuses to launch the application because he fears it will expose municipal corruption.</textarea>
                <br>
                <button class="btn-action" onclick="evaluateStudentParagraph()">Check Student Paragraph</button>

                <div id="teacher-feedback-box" style="margin-top: 18px; padding: 18px; background: #faf7f0; border: 1px solid var(--gold-border);">
                    <!-- Populated by JS -->
                </div>
            </div>
        </section>

        <!-- 3. WORK EXPERIENCE & EDUCATION (FROM CV) -->
        <section id="experience">
            <h2>Teaching Experience & Academic Background</h2>

            <div class="two-col">
                <!-- Left Column: Work Experience -->
                <div>
                    <h3>Classroom Teaching Appointments</h3>

                    <div class="cv-entry">
                        <span class="cv-date">Sep 2026 – Oct 2026</span>
                        <h4>Language & ESL Teacher / Tutor (Full-Time)</h4>
                        <p style="color: var(--ink-muted); font-style: italic; margin-bottom: 8px;">Mahanaim International School — Kasarani, Nairobi</p>
                        <ul class="classic-list">
                            <li>Delivered Cambridge IGCSE English Language and Literature lessons and prepared candidates for coursework and exams.</li>
                            <li>Provided intensive one-on-one ESL instruction for two Chinese-speaking students learning English.</li>
                        </ul>
                    </div>

                    <div class="cv-entry">
                        <span class="cv-date">Jan 2025 – Apr 2026</span>
                        <h4>Language, Literature & Pre-Technical Studies Teacher</h4>
                        <p style="color: var(--ink-muted); font-style: italic; margin-bottom: 8px;">Nyasoti Comprehensive School — Magunga, Homa Bay</p>
                        <ul class="classic-list">
                            <li>Taught Junior Secondary English, Literature, and Pre-Technical Studies (40 hrs/week) under the CBC framework.</li>
                            <li>Guided learners in essay composition, oral literature collection, and foundational technical studies.</li>
                        </ul>
                    </div>

                    <div class="cv-entry">
                        <span class="cv-date">May 2023 – Aug 2023</span>
                        <h4>Language and Literature Teacher</h4>
                        <p style="color: var(--ink-muted); font-style: italic; margin-bottom: 8px;">Ogande Girls High School — Homa Bay</p>
                        <ul class="classic-list">
                            <li>Taught Senior Secondary English and Literature (36 hrs/week), mentoring candidates in set-book discourse, critical analysis, and debate.</li>
                        </ul>
                    </div>

                    <div class="cv-entry">
                        <span class="cv-date">Jan 2020 – Mar 2020</span>
                        <h4>Language and Literature Teacher</h4>
                        <p style="color: var(--ink-muted); font-style: italic; margin-bottom: 8px;">Seka Mixed Secondary School — Magunga</p>
                        <ul class="classic-list">
                            <li>Taught secondary English and Literature and coordinated student literary and debate activities.</li>
                        </ul>
                    </div>
                </div>

                <!-- Right Column: Education, Leadership & Seminars -->
                <div>
                    <h3>University & School Education</h3>

                    <div class="cv-entry">
                        <span class="cv-date">2025 – Present</span>
                        <h4>M.A. in Applied Linguistics</h4>
                        <p style="color: var(--ink-muted); font-style: italic; margin-bottom: 6px;">Masinde Muliro University of Science and Technology (MMUST), Kakamega</p>
                        <p style="margin-bottom:0;"><strong>Thesis:</strong> <em>The Role of Social Deixis in Pragmatic Enrichment of Dholuo Polysemous Expressions.</em></p>
                    </div>

                    <div class="cv-entry">
                        <span class="cv-date">2020 – 2025</span>
                        <h4>B.Ed. (Arts) — English Language & Literature</h4>
                        <p style="color: var(--ink-muted); font-style: italic; margin-bottom: 6px;">Masinde Muliro University of Science and Technology (MMUST), Kakamega</p>
                        <p style="margin-bottom:0;"><strong>Honours:</strong> Second Class Honours (Upper Division).</p>
                    </div>

                    <div class="cv-entry">
                        <h4>Secondary & Primary Schooling</h4>
                        <p style="margin-bottom: 4px;">• <strong>KCSE (2015 – 2019):</strong> Seka Secondary School, Magunga</p>
                        <p style="margin-bottom: 0;">• <strong>KCPE (2007 – 2014):</strong> Seka Primary School, Magunga</p>
                    </div>

                    <h3 style="margin-top: 25px;">Departmental Service & Leadership</h3>
                    <div class="cv-entry">
                        <span class="cv-date">Jun 2024 – Dec 2024</span>
                        <h4>Volunteer Departmental Assistant</h4>
                        <p style="color: var(--ink-muted); font-style: italic; margin-bottom: 6px;">Department of Language and Literature, MMUST</p>
                        <p style="margin-bottom: 0;">Managed departmental records, official correspondence, and meeting schedules while serving as a liaison between lecturers and students.</p>
                    </div>

                    <div class="cv-entry">
                        <span class="cv-date">2021 – Present</span>
                        <h4>Founder & Leader — The Novel Zone</h4>
                        <p style="margin-bottom: 0;">Lead a book and intellectual discussion community; active member of the <strong>Meja Mwangi Book Club</strong> (2024–Present) and <strong>BioCosmos Kenya, MMUST Chapter</strong> (2023–Present).</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- 4. APPLIED LINGUISTICS RESEARCH & SEMINARS -->
        <section id="research">
            <h2>Linguistics Research, Certifications & Seminars</h2>
            <div class="two-col">
                <div class="cv-entry">
                    <h3>Postgraduate Research Example (Dholuo Pragmatics)</h3>
                    <p>
                        In my M.A. research at MMUST, I examine how a single polysemous Dholuo word changes meaning depending on <strong>who is speaking to whom</strong> (Social Deixis).
                    </p>
                    <p>
                        For instance, when a speaker uses kinship or status terms such as <em>Omera</em>, <em>Jaduong'</em>, or <em>Minwa</em>, listeners automatically narrow or broaden the literal dictionary meaning of the verb or noun that follows. My fieldwork combines natural recorded conversations with speaker questionnaires to map how Relevance Theory explains everyday African communication.
                    </p>
                    <p style="margin-bottom: 0;">
                        <strong>Additional Skills & Languages:</strong> English (Fluent), Kiswahili (Fluent), Dholuo (Native), Jamaican Patois (Working); Microsoft Office Suite, Power BI, Google Spreadsheets, and introductory Python for text analysis.
                    </p>
                </div>

                <div class="cv-entry">
                    <h3>Selected Workshops & Certificates (2024–2026)</h3>
                    <ul class="classic-list">
                        <li><strong>Sept 2026:</strong> Senior School Grade 11 Literature in English Webinar (Oxford University Press)</li>
                        <li><strong>Jul 2026:</strong> International Workshop on Research Methodology, Data Analysis & Publication (MAAUN)</li>
                        <li><strong>Nov 2025:</strong> Flip the Script: Worker Participation in Tech Design (SEISMEC)</li>
                        <li><strong>Oct 2025:</strong> More Than Just a Skill — Nora Wunsch-Nagy (Helbling Languages)</li>
                        <li><strong>Oct 2025:</strong> Online Grant Writing Workshop for Early and Mid-Career Researchers</li>
                        <li><strong>Feb 2025:</strong> Research Methodology and Scientific Writing (MAAUN Nigeria)</li>
                        <li><strong>Certificates Held:</strong> 120-Hour TEFL Certificate (Teacherrecords), Microsoft 365 Fundamentals, Learning to Teach Online (LinkedIn), Professional Writing (Saylor), Mental Health Awareness (Open University of Kenya), Intro to Data Analytics & AI (Simplilearn).</li>
                    </ul>
                </div>
            </div>
        </section>

        <!-- 5. PHOTO GALLERY (READY FOR YOUR PICTURES) -->
        <section id="gallery">
            <h2>Teaching, University & Book Club Photo Gallery</h2>
            <p>
                To display your pictures here, place your image files in the same folder as this file and name them <code>photo1.jpg</code>, <code>photo2.jpg</code>, <code>photo3.jpg</code>, and <code>photo4.jpg</code>.
            </p>

            <div class="gallery-grid">
                <div class="gallery-box">
                    <img src="photo1.jpg" alt="Classroom teaching" class="gallery-img-slot" onerror="this.outerHTML='<div class=\'gallery-img-slot\'>[Photo Slot 1: photo1.jpg]<br>Classroom / Literature Lesson</div>'">
                    <div class="photo-caption">Guiding students in Literature set-book analysis and essay writing.</div>
                </div>

                <div class="gallery-box">
                    <img src="photo2.jpg" alt="MMUST Department" class="gallery-img-slot" onerror="this.outerHTML='<div class=\'gallery-img-slot\'>[Photo Slot 2: photo2.jpg]<br>MMUST Graduation / Seminar</div>'">
                    <div class="photo-caption">At the Department of Language and Literature Education, MMUST, Kakamega.</div>
                </div>

                <div class="gallery-box">
                    <img src="photo3.jpg" alt="The Novel Zone Book Club" class="gallery-img-slot" onerror="this.outerHTML='<div class=\'gallery-img-slot\'>[Photo Slot 3: photo3.jpg]<br>The Novel Zone Book Club</div>'">
                    <div class="photo-caption">Leading a book discussion and debate session with The Novel Zone members.</div>
                </div>

                <div class="gallery-box">
                    <img src="photo4.jpg" alt="Oral Literature Fieldwork" class="gallery-img-slot" onerror="this.outerHTML='<div class=\'gallery-img-slot\'>[Photo Slot 4: photo4.jpg]<br>CBC Practical / ESL Session</div>'">
                    <div class="photo-caption">One-on-one ESL tutoring and Junior School CBC practical project presentation.</div>
                </div>
            </div>
        </section>

        <!-- 6. REFEREES -->
        <section id="referees" style="border-bottom: none; margin-bottom: 10px;">
            <h2>Academic & Professional Referees</h2>
            <div class="gallery-grid">
                <div class="cv-entry">
                    <h4>Dr. David Barasa</h4>
                    <p style="margin-bottom: 6px;">Associate Dean, School of Arts and Social Sciences</p>
                    <p style="font-size: 0.9rem; color: var(--ink-muted);">Masinde Muliro University of Science and Technology (MMUST), Kakamega, Kenya</p>
                    <p style="margin-bottom: 0;"><strong>Tel:</strong> <a href="tel:+254720426683">+254 720 426683</a></p>
                </div>

                <div class="cv-entry">
                    <h4>Dr. Benard Mudogo</h4>
                    <p style="margin-bottom: 6px;">Chair of Department, Language and Literature Education</p>
                    <p style="font-size: 0.9rem; color: var(--ink-muted);">Masinde Muliro University of Science and Technology (MMUST), Kakamega, Kenya</p>
                    <p style="margin-bottom: 0;"><strong>Tel:</strong> <a href="tel:+254720918907">+254 720 918907</a></p>
                </div>

                <div class="cv-entry">
                    <h4>Mr. Washington Otieno</h4>
                    <p style="margin-bottom: 6px;">English Language and Literature Teacher</p>
                    <p style="font-size: 0.9rem; color: var(--ink-muted);">Rophine International Schools, Nairobi, Kenya</p>
                    <p style="margin-bottom: 0;"><strong>Tel:</strong> <a href="tel:+254791949434">+254 791 949434</a></p>
                </div>
            </div>
        </section>

    </div>

    <!-- Simple, Error-Free Vanilla JavaScript -->
    <script>
        // 1. Switch between Lesson Plan, Exam Paper, ESL Notes, and Essay Marker
        function openDocTab(tabId, clickedButton) {
            var sheets = ['doc-lesson', 'doc-exam', 'doc-esl', 'doc-marker'];
            for (var i = 0; i < sheets.length; i++) {
                document.getElementById(sheets[i]).style.display = 'none';
            }
            var buttons = document.querySelectorAll('.tab-btn');
            for (var j = 0; j < buttons.length; j++) {
                buttons[j].classList.remove('active');
            }
            document.getElementById(tabId).style.display = 'block';
            clickedButton.classList.add('active');
        }

        // 2. Toggle Teacher's Marking Scheme on Grade 8 Exam Paper
        function toggleMarkingScheme() {
            var box = document.getElementById('marking-scheme');
            if (box.style.display === 'block') {
                box.style.display = 'none';
            } else {
                box.style.display = 'block';
            }
        }

        // 3. Evaluate Student Essay Paragraph
        function evaluateStudentParagraph() {
            var text = document.getElementById('student-paragraph').value.trim();
            var feedbackBox = document.getElementById('teacher-feedback-box');

            if (!text) {
                feedbackBox.innerHTML = "<p>Please paste or type a student paragraph above first.</p>";
                return;
            }

            var words = text.match(/\b\w+\b/g) || [];
            var sentences = text.split(/[.!?]+/).filter(function(s) { return s.trim().length > 0; });
            var wordCount = words.length;
            var sentenceCount = Math.max(sentences.length, 1);
            var avgLen = (wordCount / sentenceCount).toFixed(1);

            // Check for evidence/transition words used in literature essays
            var lower = text.toLowerCase();
            var hasEvidence = lower.indexOf('for example') !== -1 || lower.indexOf('for instance') !== -1 || lower.indexOf('when ') !== -1 || text.indexOf('"') !== -1;
            var hasContrast = lower.indexOf('however') !== -1 || lower.indexOf('although') !== -1 || lower.indexOf('instead') !== -1 || lower.indexOf('yet') !== -1;

            var teacherNote = "";
            if (wordCount < 30) {
                teacherNote = "This paragraph is a bit brief for a Senior School literature point. Expand your explanation of the character's motive.";
            } else if (hasEvidence && hasContrast) {
                teacherNote = "Strong PEEE structure! You have a clear point, a textual illustration, and a contrast connector showing analytical depth.";
            } else if (!hasEvidence) {
                teacherNote = "Good topic sentence, but remember to support your claim with a specific scene or quotation from the set book (e.g., 'For example, in Act 1...').";
            } else {
                teacherNote = "Well-constructed paragraph. Try adding a concluding sentence that links back to the playwright's main theme.";
            }

            feedbackBox.innerHTML =
                "<p style='margin-bottom:6px;'><strong>Word Count:</strong> " + wordCount + " words &nbsp;|&nbsp; <strong>Sentences:</strong> " + sentenceCount + " &nbsp;|&nbsp; <strong>Average Sentence Length:</strong> " + avgLen + " words</p>" +
                "<p style='margin-bottom:6px;'><strong>Textual Illustration Present:</strong> " + (hasEvidence ? "Yes ✓" : "Needs specific example/quote") + " &nbsp;|&nbsp; <strong>Analytical Connector Used:</strong> " + (hasContrast ? "Yes ✓" : "None detected") + "</p>" +
                "<p style='margin-bottom:0; color: var(--maroon);'><strong>Mr. Odhiambo's Margin Comment:</strong> <em>\"" + teacherNote + "\"</em></p>";
        }

        // Run once on load so the feedback box is populated
        evaluateStudentParagraph();
    </script>
</body>
</html>
