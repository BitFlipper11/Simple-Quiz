#include <stdio.h>

// Function to display the quiz questions and return the score
int startQuiz() {
    int score = 0;
    int answer;

    printf("Welcome to the Quiz Game!\n");
    printf("Please answer the following questions:\n\n");

    // Question 1
    printf("1. Who won the Champions League in 2024?\n");
    printf("1) FC Barcelona\n");
    printf("2) PSG\n");
    printf("3) Real Madrid\n");
    printf("4) Manchester City\n");
    printf("Your answer: ");
    scanf("%d", &answer);
    if (answer == 3) {
        printf("Correct!\n");
        score++;
    } else {
        printf("Wrong! The correct answer is 3) Paris.\n");
    }

    // Question 2
    printf("\n2. Who won La Liga in 2024?\n");
    printf("1) Atletico Madrid\n");
    printf("2) Real Madrid\n");
    printf("3) Espanyol\n");
    printf("4) FC Barcelona\n");
    printf("Your answer: ");
    scanf("%d", &answer);
    if (answer == 2) {
        printf("Correct!\n");
        score++;
    } else {
        printf("Wrong! The correct answer is 2) Mars.\n");
    }

    // Question 3
    printf("\n3. Who knocked out Manchester City from Champions League in 2025?\n");
    printf("1) Real Madrid\n");
    printf("2) Manchester United\n");
    printf("3) Juventus\n");
    printf("4) Inter\n");
    printf("Your answer: ");
    scanf("%d", &answer);
    if (answer == 1) {
        printf("Correct!\n");
        score++;
    } else {
        printf("Wrong! The correct answer is 1) Harper Lee.\n");
    }

    return score;
}

int main() {
    int score = startQuiz();
    printf("\nQuiz Over! You scored %d out of 3.\n", score);
    return 0;
}
