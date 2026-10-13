# Experiment 4: Prompt Failure Diagnosis and Edge Cases

## Aim
To identify prompt failures and improve prompts using the Gemini API.

## Description
This experiment tests original prompts and corrected prompts using the same language model. It examines hallucination, instruction-following errors, and over-refusal.

## Technologies Used
- Python
- Google Colab
- Gemini API
- Google Gen AI SDK

## Test Cases
1. **Hallucination:** Asking who won the FIFA World Cup in 1942.
2. **Instruction Following:** Asking for the three largest oceans using exactly three bullet points.
3. **Over-Refusal:** Asking for a school-appropriate fun fact about the Roman Empire.

## Procedure
1. Configure the Gemini API key securely in Google Colab Secrets.
2. Send each original prompt to the Gemini model.
3. Examine the response for possible failures.
4. Create a corrected prompt for each test case.
5. Compare the original and corrected responses.

## Expected Result
The experiment demonstrates how prompt corrections can improve factual accuracy, instruction-following, and appropriate responses. Actual results may vary depending on the model.

## Conclusion
Prompt diagnosis and refinement help identify possible weaknesses in language-model responses and improve prompt quality.

## How to Run
Open `experiment4.ipynb` in Google Colab, add your `GEMINI_API_KEY` in Colab Secrets, and run the notebook cells.

**Security:** Never upload your actual API key to GitHub.
