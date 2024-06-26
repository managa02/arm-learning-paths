---
# ================================================================================
#       Edit
# ================================================================================

# Always 3 questions. Should try to test the reader's knowledge, and reinforce the key points you want them to remember.
    # question:         A one sentence question
    # answers:          The correct answers (from 2-4 answer options only). Should be surrounded by quotes.
    # correct_answer:   An integer indicating what answer is correct (index starts from 0)
    # explanation:      A short (1-3 sentence) explanation of why the correct answer is correct. Can add additional context if desired


review:
    - questions:
        question: >
            Envoy can only be installed by building it from source.
        answers:
            - "True"
            - "False"
        correct_answer: 2                     
        explanation: >        
            Envoy can be installed from the package manager or built from source.

    - questions:
        question: >
            To build Envoy from source, you'll require the Bazel build tool.
        answers:
            - "True"
            - "False"
        correct_answer: 1                     
        explanation: >        
            Bazel is the build tool used for constructing Envoy.

    - questions:
        question: >
            To run Envoy as a service, you'll need a config file.
        answers:
            - "True"
            - "False"
        correct_answer: 1
        explanation: >
            You will need to either create a config file or use a sample config to run Envoy as a service.
                    

# ================================================================================
#       FIXED, DO NOT MODIFY
# ================================================================================
title: "Review"                 # Always the same title
weight: 20                      # Set to always be larger than the content in this path
layout: "learningpathall"       # All files under learning paths have this same wrapper
---

