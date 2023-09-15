def chadbot(user_inp):
    user_inp = user_inp.lower()
    rules = {
        'hello': 'Hello! How can I help you?',
        'can you tell me a joke': 'No! HAHAHA',
        'goodbye': 'Goodbye! Have a nice day!',
        'what is your name': 'My name is ChadBot.',
        'how does the internet work': 'The internet is a global network of computers connected through various'
                                      'technologies like TCP/IP.',
        "what's the capital of france": 'The capital of France is Paris.',
        "what is the square root of 16": 'The square root of 16 is 4.',
        "what is the population of china": 'The population of China is over 1.4 billion people.',
        'what is the chemical formula for water': 'The chemical formula for water is H2O.',
        'how many planets are in the solar system': 'There are eight planets in the solar system: Mercury, Venus,'
                                                    ' Earth, Mars, Jupiter, Saturn, Uranus, and Neptune.',
        'what is the tallest mountain in the world': 'The tallest mountain in the world is Mount Everest, which is '
                                                     'located in the Himalayas between Nepal and China. It is '
                                                     '8,848 meters (29,029 feet) tall.',
        "translate hello to french": "Hello in French is 'Bonjour.'",
        "most commonly used programming languages in the world": "JavaScript, Python, Java, C#, PHP, "
                                                                "C++, Ruby",
        'calculate the square root of 144.': 'The square root of 144 is 12.',
        'what is the largest desert in the world': 'The largest desert in the world is the Sahara Desert, which is '
                                                   'located in North Africa. It covers an area of over 9 million '
                                                   'square kilometers (3.5 million square miles).',
        'what is the fastest animal on earth': 'The fastest animal on Earth is the peregrine falcon, which can reach'
                                         'speeds of up to 320 kilometers per hour (200 miles per hour) when diving.',
        'what is the most popular sport in the world': 'The most popular sport in the world is soccer, which is '
                                                       'played by over 265 million people.',
        'what is the most expensive painting in the world': 'The most expensive painting in the world is Salvator '
                                                    'Mundi by Leonardo da Vinci, which sold for $450.3 million in 2017.',
        "full form of un": 'United Nations'
    }

    for rule, response in rules.items():
        if rule in user_input:
            return response

    return 'I am not sure what you mean. Please try again.'


while True:
    user_input = input('What can I do for you? ')
    response = chadbot(user_input)
    print(response)
