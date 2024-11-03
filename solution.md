**TODO:** 1) Print the first 10 names. Find out the number of names contained in the dataset as well as the shortest and longest name. **(2 points)**

---

YOUR CODE GOES HERE
print("First 10 names in the dataset: ", words[:10])
print("Number of names contained in the dataset: ", len(words))
print("Longest name in the dataset: ", max(words, key=len))
print("Shortest name in the dataset: ",min(words, key=len))

---

