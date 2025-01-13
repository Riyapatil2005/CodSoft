import java.util.Random;
import java.util.Scanner;

public class NumberGuessingGame {

    // ANSI escape codes for colors
    private static final String RESET = "\u001B[0m";
    private static final String GREEN = "\u001B[32m";
    private static final String RED = "\u001B[31m";
    private static final String YELLOW = "\u001B[33m";
    private static final String BLUE = "\u001B[34m";

    // Function to play a single round of the game
    public static int playRound(int lowerBound, int upperBound, int maxAttempts) {
        Random rand = new Random();
        int numberToGuess = rand.nextInt(upperBound - lowerBound + 1) + lowerBound; // Random number between lowerBound and upperBound
        Scanner scanner = new Scanner(System.in);
        int attempts = 0;
        boolean guessedCorrectly = false;

        System.out.println(BLUE + "------------------------------------");
        System.out.println("Guess the number between " + lowerBound + " and " + upperBound + ":");
        System.out.println("------------------------------------" + RESET);

        // Start the guessing loop
        while (attempts < maxAttempts && !guessedCorrectly) {
            attempts++;
            System.out.print(YELLOW + "Attempt " + attempts + ": Enter your guess: " + RESET);
            int userGuess = scanner.nextInt();

            if (userGuess < numberToGuess) {
                System.out.println(RED + "Your guess is too low. Try again!" + RESET);
            } else if (userGuess > numberToGuess) {
                System.out.println(RED + "Your guess is too high. Try again!" + RESET);
            } else {
                guessedCorrectly = true;
                System.out.println(GREEN + "Congratulations! You guessed the correct number: " + numberToGuess + RESET);
            }

            if (attempts == maxAttempts && !guessedCorrectly) {
                System.out.println(RED + "Sorry! You've used all attempts. The correct number was " + numberToGuess + RESET);
            }
        }

        // Return score: maxAttempts - attempts + 1 if correct, 0 if incorrect
        if (guessedCorrectly) {
            return maxAttempts - attempts + 1;
        } else {
            return 0;
        }
    }

    // Main game loop to allow multiple rounds
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        int totalRounds = 0;
        int roundsWon = 0;
        int totalScore = 0;
        boolean playAgain = true;
        int lowerBound = 1;
        int upperBound = 100;
        int maxAttempts = 10; // Limit of 10 attempts per round

        // Display game welcome message
        System.out.println(GREEN + "Welcome to the Number Guessing Game!" + RESET);
        System.out.println("You will have " + maxAttempts + " attempts to guess the correct number.");
        System.out.println("Let's begin!\n");

        while (playAgain) {
            totalRounds++;
            System.out.println(BLUE + "\n--- Round " + totalRounds + " ---" + RESET);
            int score = playRound(lowerBound, upperBound, maxAttempts);

            // Update the score and the number of rounds won
            if (score > 0) {
                roundsWon++;
            }
            totalScore += score;

            System.out.println(YELLOW + "Your score for this round: " + score + RESET);
            System.out.println("Total score: " + totalScore + "\n");

            // Ask if the user wants to play another round
            System.out.print("Would you like to play another round? (yes/no): ");
            String response = scanner.next().toLowerCase();
            if (response.equals("no")) {
                playAgain = false;
            }
        }

        // Display the final score and number of rounds won
        System.out.println(GREEN + "\nGame Over! You played " + totalRounds + " rounds." + RESET);
        System.out.println(YELLOW + "You won " + roundsWon + " rounds." + RESET);
        System.out.println("Your total score: " + totalScore + "\n");
        System.out.println(GREEN + "Thanks for playing!" + RESET);
    }
}
