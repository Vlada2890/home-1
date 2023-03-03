# home-1
def read_f(*f):
    for f in f:
        with open(f, 'r') as f:
            print(f.read())

def count_words(file12):
    with open(file12, 'r') as f:
        text = f.read()
        words56 = text.split()
        return len(words56)

def words11(file):

    with open(file, 'r') as f:
        text = f.read()
        words = text.split()
        words1 = [word for word in words if len(word) < 4]
        print(' '.join(words1))

def cap_words(file):
    with open(file, 'r') as f:
        txt = f.read()
        word11 = txt.split()
        cap_words1 = [word for word in word11 if word[0].isupper()]
        return len(cap_words1)
