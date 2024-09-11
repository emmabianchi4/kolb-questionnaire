<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kolb's Learning Style Questionnaire</title>
    <style>
        body { font-family: Arial, sans-serif; line-height: 1.6; padding: 20px; max-width: 800px; margin: 0 auto; }
        h1 { color: #333; }
        form { background: #f4f4f4; padding: 20px; border-radius: 8px; }
        label { display: block; margin-bottom: 10px; }
        button { background: #333; color: #fff; padding: 10px 20px; border: none; cursor: pointer; }
        #results { margin-top: 20px; }
    </style>
</head>
<body>
    <h1>Kolb's Learning Style Questionnaire</h1>
    <p>This questionnaire is designed to find out your preferred learning style(s) as an adult. Please answer honestly. There are no right or wrong answers. If you agree more than you disagree with a statement, select 'Agree'. If you disagree more than you agree, select 'Disagree'.</p>
    <form id="kolbForm">
        <!-- Questions will be dynamically inserted here by JavaScript -->
    </form>
    <button onclick="calculateScores()">Submit</button>
    <div id="results"></div>

    <script>
        const questions = [
            "I have strong beliefs about what is right and wrong, good and bad.",
            "I often act without considering the possible consequences.",
            "I tend to solve problems using a step-by-step approach.",
            "I believe that formal procedures and policies restrict people.",
            "I have a reputation for saying what I think, simply and directly.",
            "I often find that actions based on feelings are as sound as those based on careful thought and analysis.",
            "I like the sort of work where I have time for thorough preparation and implementation.",
            "I regularly question people about their basic assumptions.",
            "What matters most is whether something works in practice.",
            "I actively seek out new experiences.",
            "When I hear about a new idea or approach, I immediately start working out how to apply it in practice.",
            "I am keen on self discipline such as watching my diet, taking regular exercise, sticking to a fixed routine, etc.",
            "I take pride in doing a thorough job.",
            "I get on best with logical, analytical people and less well with spontaneous, 'irrational' people.",
            "I take care over how I interpret data and avoid jumping to conclusions.",
            "I like to reach a decision carefully after weighing up many alternatives.",
            "I am attracted more to novel, unusual ideas than to practical ones.",
            "I don't like disorganised things and prefer to fit things into a coherent pattern.",
            "I accept and stick to laid down procedures and policies so long as I regard them as an efficient way of getting the job done.",
            "I like to relate my actions to a general principle, standard or belief.",
            "In discussions, I like to get straight to the point.",
            "I tend to have distant, rather formal relationships with people at work.",
            "I thrive on the challenge of tackling something new and different.",
            "I enjoy fun-loving spontaneous people.",
            "I pay careful attention to detail before coming to a conclusion.",
            "I find it difficult to produce ideas on impulse.",
            "I believe in coming to the point immediately.",
            "I am careful not to jump to conclusions too quickly.",
            "I prefer to have as many sources of information as possible – the more information to think over the better.",
            "Flippant, superficial people who don't take things seriously enough usually irritate me.",
            "I listen to other people's points of view before putting my own view forward.",
            "I tend to be open about how I'm feeling.",
            "In discussions, I enjoy watching the plotting and scheming of the other participants.",
            "I prefer to respond to events in a spontaneous, flexible way rather than plan things out in advance.",
            "I tend to be attracted to techniques such as flow charts, contingency plans etc.",
            "It worries me if I have to rush work to meet a tight deadline.",
            "I tend to judge people's ideas on their practical merits.",
            "Quiet, thoughtful people tend to make me feel uneasy.",
            "I often get irritated by people who want to rush things.",
            "It is more important to enjoy the present moment than to think about the past or future.",
            "I think that decisions based on a careful analysis of all the information are better than those based on intuition.",
            "I tend to be a perfectionist.",
            "In discussions, I usually produce lots of spontaneous ideas.",
            "In meetings, I put forward practical, realistic ideas.",
            "More often than not, rules are there to be broken.",
            "I prefer to stand back from a situation and consider all the perspectives.",
            "I can often see inconsistencies and weaknesses in other people's arguments.",
            "On balance I talk more than I listen.",
            "I can often see better, more practical ways to get things done.",
            "I think written reports should be short and to the point.",
            "I believe that rational, logical thinking should win the day.",
            "I tend to discuss specific things with people rather than engaging in social discussion.",
            "I like people who approach things realistically rather than theoretically.",
            "In discussions, I get impatient with irrelevant issues and digressions.",
            "If I have a report to write, I tend to produce lots of drafts before settling on the final version.",
            "I am keen to try things out to see if they work in practice.",
            "I am keen to reach answers via a logical approach.",
            "I enjoy being the one that talks a lot.",
            "In discussions, I often find I am a realist, keeping people to the point and avoiding wild speculations.",
            "I like to ponder many alternatives before making up my mind.",
            "In discussions with people I often find I am the most dispassionate and objective.",
            "In discussions I'm more likely to adopt a 'low profile' than to take the lead and do most of the talking.",
            "I like to be able to relate current actions to the longer-term bigger picture.",
            "When things go wrong, I am happy to shrug it off and 'put it down to experience'.",
            "I tend to reject wild, spontaneous ideas as being impractical.",
            "It's best to think carefully before taking action.",
            "On balance, I do the listening rather than the talking.",
            "I tend to be tough on people who find it difficult to adopt a logical approach.",
            "Most times I believe the end justifies the means.",
            "I don't mind hurting people's feelings so long as the job gets done.",
            "I find the formality of having specific objectives and plans stifling.",
            "I'm usually one of the people who puts life into a party.",
            "I do whatever is practical to get the job done.",
            "I quickly get bored with methodical, detailed work.",
            "I am keen on exploring the basic assumptions, principles and theories underpinning things and events.",
            "I'm always interested to find out what people think.",
            "I like meetings to be run on methodical lines, sticking to laid down agenda.",
            "I steer clear of subjective (biased) or ambiguous (unclear) topics.",
            "I enjoy the drama and excitement of a crisis situation.",
            "People often find me insensitive to their feelings."
        ];

        const scoringKey = {
            activist: [2, 4, 6, 10, 17, 23, 24, 32, 34, 38, 40, 43, 45, 48, 58, 64, 71, 72, 74, 79],
            reflector: [7, 13, 15, 16, 25, 28, 29, 31, 33, 36, 39, 41, 46, 52, 55, 60, 62, 66, 67, 76],
            theorist: [1, 3, 8, 12, 14, 18, 20, 22, 26, 30, 42, 47, 51, 57, 61, 63, 68, 75, 77, 78],
            pragmatist: [5, 9, 11, 19, 21, 27, 35, 37, 44, 49, 50, 53, 54, 56, 59, 65, 69, 70, 73, 80]
        };

        function createForm() {
            const form = document.getElementById('kolbForm');
            questions.forEach((question, index) => {
                const questionHtml = `
                    <div>
                        <p>${index + 1}. ${question}</p>
                        <label>
                            <input type="radio" name="q${index + 1}" value="agree" required> Agree
                        </label>
                        <label>
                            <input type="radio" name="q${index + 1}" value="disagree" required> Disagree
                        </label>
                    </div>
                `;
                form.innerHTML += questionHtml;
            });
        }

        function calculateScores() {
            const scores = {activist: 0, reflector: 0, theorist: 0, pragmatist: 0};
            Object.keys(scoringKey).forEach(style => {
                scoringKey[style].forEach(questionNumber => {
                    const answer = document.querySelector(`input[name="q${questionNumber}"]:checked`);
                    if (answer && answer.value === 'agree') {
                        scores[style]++;
                    }
                });
            });
            displayResults(scores);
        }

        function displayResults(scores) {
            const resultsDiv = document.getElementById('results');
            resultsDiv.innerHTML = '<h2>Your Learning Style Preferences:</h2>';
            Object.keys(scores).forEach(style => {
                resultsDiv.innerHTML += `<p>${style.charAt(0).toUpperCase() + style.slice(1)}: ${scores[style]}</p>`;
            });
            
            resultsDiv.innerHTML += '<h3>Interpretation:</h3>';
            resultsDiv.innerHTML += '<p>Scores for each learning style range from 0 to 20:</p>';
            resultsDiv.innerHTML += '<ul>';
            resultsDiv.innerHTML += '<li>0-6: Very low preference</li>';
            resultsDiv.innerHTML += '<li>7-9: Low preference</li>';
            resultsDiv.innerHTML += '<li>10-13: Moderate preference</li>';
            resultsDiv.innerHTML += '<li>14-15: Strong preference</li>';
            resultsDiv.innerHTML += '<li>16-20: Very strong preference</li>';
            resultsDiv.innerHTML += '</ul>';
            resultsDiv.innerHTML += '<p>Your highest score(s) indicate your preferred learning style(s).</p>';
        }

        createForm();
    </script>
</body>
</html>
