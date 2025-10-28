def shortest_word(texT):
    words = text.split()
    return min(words, key=len)

if __name__ == "__main__":
    sample = "GitHub daily commits improve consistency"
    print(f"Shortest word: {shortest_word(sample)}")
