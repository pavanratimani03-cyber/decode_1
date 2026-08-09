# decode_1
interenship work


while True:
    try:
        a = input("Ask a question (or type 'exit' to quit): ").lower().strip()

        if a == "exit":
            print("Goodbye!")
            break

        elif a == "hi" or a == "hello":
            print("Hi! What can I do for you?")

        elif a == "what is your name":
            print("I am your chatbot.")

        elif a == "what is your age":
            print("I am a computer program, so I don't have an age.")

        elif a == "what is your occupation":
            print("I am a chatbot to help you with your queries.")
        elif a== "how to make gf":
            print("it is totally impossible")
        elif a== "how to understand womens":
            print("we also searching")
        else:
            print("I'm sorry, I don't understand your question.")

    except Exception:
        print("Please enter a valid question.")
