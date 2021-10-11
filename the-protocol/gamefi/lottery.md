# Lottery

The Casino counts with a Lottery system with burning mechanisms that works as follows: To win the lottery jackpot (60% of the entire lottery pool), users need to match all 4 numbers on their tickets in the same position as the 4 winning numbers. However, if you don’t match all 4, know that as long as you match 2 or more numbers in the correct position, you are guaranteed to win a reward.

**Information**

* Lottery Ticket Fee: TBA
* Entry Limit: No limit
* Paying for one ticket will give users a random 4 digit combination with each digit being between 1-14, for e.g. “3-2-7-9”. Users can buy multiple tickets in one go.
* Each full lottery session is completed every 24 hours at 4 PM (EST).

**Winning Ratio**

* Match all 4 numbers in the exact order = win or split 50% of the pot.
* Match 3 numbers in the exact order = win or split 20% of the pot.
* Match 2 numbers in the exact order = win or split 10% of the pot.
* Burn the remaining 20% of the pot.

In the event that no participants were able to match 3 numbers on any draw, the 20% allocated to winners will then be burned.

**How are ticket numbers drawn?**

The lottery aims to be completely random. Even though the ticket numbers given out are determined by a front-end logic, there is an extremely low chance that anyone is able to determine the 4 winning numbers ahead of time.

* The 1st lottery number will be determined based on the %10 remainder of a hash encoded by the blockhash and the number of participating users at the entry deadline.
* The 2nd lottery number will be determined based on the %10 remainder of a hash encoded by the blockhash and the total pooled Golden Egg balance at the entry deadline.
* The 3rd lottery number will be determined based on the %10 remainder of a hash encoded by the blockhash and the timestamp of the last lottery participant at the entry deadline.
* The 4th lottery number will be determined based on the %10 remainder of a hash encoded by the blockhash and the block difficulty at the entry deadline.
