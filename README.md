def medical_nurse_chatbot():
    print("Welcome to the Medical Nurse Chatbot!")
    print("You can ask about common health issues. Type 'exit' to end the conversation.")
    
    while True:
        question = input("\nWhat is your question? ").strip().lower()
        
        if question == 'exit':
            print("Thank you for using the Medical Nurse Chatbot. Stay healthy!")
            break
        elif "fever" in question:
            print("A fever is usually a sign of infection. Stay hydrated and rest. If it persists, consult a doctor.")
        elif "cough" in question:
            print("A cough can be caused by various issues. Stay hydrated and consider over-the-counter remedies. If it lasts more than a week, see a doctor.")
        elif "headache" in question:
            print("Headaches can be caused by stress, dehydration, or other factors. Drink water and rest. If severe, consult a healthcare professional.")
        elif "stomach ache" in question:
            print("Stomach aches can result from various causes, including indigestion. Try to rest and avoid heavy meals. Consult a doctor if it persists.")
        elif "cold" in question:
            print("Common colds are usually viral. Rest, drink fluids, and consider over-the-counter medications for relief.")
        elif "fatigue" in question:
            print("Fatigue can result from various factors including lack of sleep, stress, or medical conditions. Ensure adequate rest and consult a doctor if it continues.")
        elif "allergy" in question:
            print("Allergies can cause various symptoms. Identify triggers, avoid them, and consider antihistamines. Consult a doctor for severe reactions.")
        else:
            print("I'm sorry, I don't have information on that. Please consult a healthcare professional.")

if __name__ == "__main__":
    medical_nurse_chatbot()
