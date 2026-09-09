# Dindu Gowtham Kanuri

## Favorite Actor: Robert Downey Jr.

Robert Downey Jr. is my favorite actor because he makes his characters **interesting** and entertaining. I especially like his role as **Iron Man** because of his confidence, and acting style.

---

## Favorite Movies

1. Avengers: Endgame
2. Iron Man
3. Spider-Man: No Way Home

## Favorite Songs

- Blinding Lights
- Believer
- Counting Stars

---

## Favorite City

[Read about my favorite city](MyCity.md)

---

## Cities I Would Like To Visit

There are many cities I would like to visit in the future. I enjoy places with beaches, beautiful views, good food, and interesting things to do.

| City | Reason | Distance from Miami | Estimated Visit Cost |
|---|---|---|---|
| Naples, Italy | Beautiful coast, food, and historic places | About 5,200 miles | About $1,500 |
| Barcelona, Spain | Beaches, architecture, and city life | About 4,700 miles | About $1,400 |
| Cape Town, South Africa | Beaches, mountains, and ocean views | About 7,600 miles | About $1,800 |
| Honolulu, Hawaii | Beaches, warm weather, and outdoor activities | About 4,850 miles | About $1,600 |

---

## Favorite Sayings

### Albert Einstein

> Life is like riding a bicycle. To keep your balance, you must keep moving.

### Steve Jobs

> Stay hungry. Stay foolish.

---

## Eight Queens Code Example

This Java code is an example of the N-Queens problem. It finds a way to place queens on a chessboard so that they do not attack each other.

```java
import java.util.Arrays;
import java.util.ArrayList;

public class EightQueens {


	public static void main(String[] args) {
			solveNQueens(8);
			ArrayList<char[][]> solutions = getAllNQueens(8);
			System.out.println( solutions.size() );
			for( int i = 0; i < solutions.size(); i++){
				System.out.println("\n\nSolution " + (i+1));
				if( queensAreSafe(solutions.get(i)) )
					printBoard(solutions.get(i));
				else
```

[Eight Queens Code Source](https://www.cs.utexas.edu/~scottm/cs307/javacode/codeSamples/EightQueens.java)
