# if-statement-program-1\
#This program gets the average of three test scores and display
#their average. It congratulates the user if the average is a high score
#The constant High_Score, hold the value that is considerd high score

#get the high score
High_Score = 95

# Get the three test scores
test1 = int(input('Enter test score 1:'))
test2 = int(input('Enter test score 2:'))
test3 = int(input('Enter test score 3:'))

#Calculate the average test score
average = (test1 + test2 + test3) / 3

#print average
print(f'The average score is {average:2f}.')

#if average is a high score, congratulate the user
if average >= High_Score:
    print('Congratulations, you rock!')
    
