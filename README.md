# Pharos Natural Language Payment Agent

An intelligent payment routing agent developed in **Java** for the Pharos Agent Arena designed to parse natural language instructions into fully prepared, unsigned transactions[cite: 11].

## 📋 Requirements Met

1. **Natural Language Parsing & Ambiguity Handling (Req. 01):** Analyzes amount, token, and recipient from free-form text and requests clarification when instructions are ambiguous[cite: 11].
2. **Request Validation (Req. 02):** Validates recipient formats, token contracts, and ensures sufficient wallet balance before proceeding[cite: 11].
3. **Human-Readable Summary (Req. 03):** Presents a clear summary for the user to review prior to generating the unsigned transaction[cite: 11].
4. **Non-Signing Safety (Req. 04):** Never signs or submits transactions automatically; outputs strictly unsigned transaction payloads or wallet signature requests[cite: 11].

## 🚀 How to Run

1. Certifique-se de ter o **Java JDK** instalado.
2. Compile o ficheiro:
   ```bash
   javac NaturalLanguagePaymentAgent.java
