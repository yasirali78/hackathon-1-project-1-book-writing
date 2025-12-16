// Hackathon 1 – Project 1: Book Writing (TypeScript Version)

// Author: Yasir Ali
// Book Title: Growth Mindset & Digital Discipline

// ----------------------------
// Chapter Interface
interface Chapter {
    title: string;
    content: string[];
}

// ----------------------------
// Chapters Data
const bookChapters: Chapter[] = [
    {
        title: 'Preface',
        content: [
            'This book is written for students, beginners, and creators who want to improve their life, learning, and digital habits.',
            'Success depends on mindset, consistency, and discipline.'
        ]
    },
    {
        title: 'Chapter 1: What is a Growth Mindset?',
        content: [
            'A growth mindset is the belief that abilities can be developed through effort, learning, and persistence.',
            'Skills improve with practice.',
            'Failure is a lesson, not the end.',
            'Learning never stops.'
        ]
    },
    {
        title: 'Chapter 2: Fixed vs Growth Mindset',
        content: [
            'Fixed Mindset: Believes intelligence is limited, avoids challenges, gives up easily.',
            'Growth Mindset: Believes intelligence can grow, accepts challenges, keeps improving.'
        ]
    },
    {
        title: 'Chapter 3: Power of Daily Habits',
        content: [
            'Small daily habits create big changes.',
            'Read 10 minutes daily.',
            'Write daily goals.',
            'Learn new skills regularly.'
        ]
    },
    {
        title: 'Chapter 4: Digital Discipline',
        content: [
            'Use technology wisely.',
            'Set screen time limits.',
            'Avoid unnecessary scrolling.',
            'Focus on learning.'
        ]
    },
    {
        title: 'Chapter 5: Learning from Failure',
        content: [
            'Failure is part of success.',
            'Steps: Accept mistakes, analyze, improve, try again.'
        ]
    },
    {
        title: 'Chapter 6: Consistency',
        content: [
            'Consistency is more powerful than motivation.',
            'Small effort × Daily practice = Big success.'
        ]
    },
    {
        title: 'Chapter 7: Self-Confidence',
        content: [
            'Confidence grows when you prepare, practice, and learn continuously.',
            'Set achievable goals.',
            'Celebrate small wins.',
            'Learn from criticism.'
        ]
    },
    {
        title: 'Chapter 8: Skills & Education',
        content: [
            'Modern success depends on skills:',
            'Communication, Problem-solving, Technology, Critical thinking.'
        ]
    },
    {
        title: 'Chapter 9: Discipline in Student Life',
        content: [
            'A disciplined student manages time, focuses on goals, and avoids distractions.',
            'Plan daily schedule, study with focus, revise lessons.'
        ]
    },
    {
        title: 'Chapter 10: Conclusion',
        content: [
            'Success is not achieved overnight.',
            'With growth mindset, strong habits, and digital discipline, anyone can improve life.',
            'Start small, stay consistent, and believe in yourself.'
        ]
    }
];

// ----------------------------
// Function to display book
function displayBook(book: Chapter[]) {
    book.forEach(chapter => {
        console.log(`\n=== ${chapter.title} ===\n`);
        chapter.content.forEach(paragraph => console.log(paragraph));
    });
}

// ----------------------------
// Run the Book
displayBook(bookChapters);
