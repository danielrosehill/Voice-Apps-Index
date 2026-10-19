# Voice Apps Index

[![Master Index](https://img.shields.io/badge/Master_Index-GitHub-blue?style=for-the-badge&logo=github)](https://github.com/danielrosehill/Index)

Index of voice typing, dictation, and speech-to-text applications and utilities.

---

## Active Projects

Three parallel tracks, each with its own use case:

- **Real-time streaming at cursor** — speak and see text appear as you go, for chat, IDEs, and quick input. Covered by **Parlance** (local-only, Parakeet).
- **Long-form note dictation** — speak a full note, get back polished, formatted text in one pass. Covered by **AI Typer V2**.
- **Android voice-to-text reformatter** — hold-to-talk, single-pass transcription + reformatting into a chosen preset (email, prompt, to-do, Hebrew). Covered by **Voxcast**.

### Parlance

The local-only track — on-device dictation with NVIDIA Parakeet TDT 0.6B v2 via sherpa-onnx (int8), no cloud and no GPU required. Android voice keyboard (IME) plus a Linux/Windows tray app with hotkey or foot-pedal dictation. Choice of stock Parakeet or the English-Hebrew code-switching fine-tune. Replaces Parakeet Type Ubuntu and Voice To Hebrish.

[![View Repo](https://img.shields.io/badge/View_Repo-GitHub-181717?style=for-the-badge&logo=github)](https://github.com/danielrosehill/Parlance-Dictation)

---

### AI Typer V2

The long-form dictation track — single-pass multimodal audio understanding (Gemini via OpenRouter) where the model transcribes and formats in one call. Smart format detection (email / list / notes), VAD + AGC preprocessing, optional second-pass coherence review, custom dictionary with CSV import/export, streaming live-text preview, global F13–F24 hotkeys, append mode, and type-at-cursor that works in terminals as well as GUI apps.

[![View Repo](https://img.shields.io/badge/View_Repo-GitHub-181717?style=for-the-badge&logo=github)](https://github.com/danielrosehill/AI-Typer-V2)

---

### Voxcast

The Android mobile track — a hold-to-talk voice-to-text app (Expo / React Native) that transcribes and reformats in a single OpenRouter call (Gemini 3.1 Flash Lite) into one of eight serious presets: business email, AI prompt, dev prompt, basic cleanup, to-do list, note to self, casual Hebrew, and Hebrew email. Email modes return separate subject + body for two-tap copy. One preset active at a time, no layering. Sibling project to Crazy-Keyboard but reframed as a productivity tool.

[![View Repo](https://img.shields.io/badge/View_Repo-GitHub-181717?style=for-the-badge&logo=github)](https://github.com/danielrosehill/Voxcast)

---

## Earlier Iterations

Kept for reference — superseded by the active projects above.

### Thought Pad

Two-stage process for creating notes from dictated speech — transcription via Whisper API followed by light text formatting. Exports to markdown. Predecessor to AI Typer V2.

[![View Repo](https://img.shields.io/badge/View_Repo-GitHub-181717?style=for-the-badge&logo=github)](https://github.com/danielrosehill/Thought-Pad)

---

## Transcription Tools

### DVR Transcriber

Workflow workspace for importing recordings from a DVR and using AI for transcription.

[![View Repo](https://img.shields.io/badge/View_Repo-GitHub-181717?style=for-the-badge&logo=github)](https://github.com/danielrosehill/DVR-Transcriber)

---

### ASR Transcription Pipeline

ASR transcription pipeline.

[![View Repo](https://img.shields.io/badge/View_Repo-GitHub-181717?style=for-the-badge&logo=github)](https://github.com/danielrosehill/ASR-Transcription-Pipeline)

---

## Transcription MCPs

### Gemini Transcription MCP

MCP server for Gemini multimodal audio transcription with built-in post-processing.

[![View Repo](https://img.shields.io/badge/View_Repo-GitHub-181717?style=for-the-badge&logo=github)](https://github.com/danielrosehill/Gemini-Transcription-MCP)

---

### Cloud ASR MCP

MCP for using various cloud ASR models for speech-to-text and transcription.

[![View Repo](https://img.shields.io/badge/View_Repo-GitHub-181717?style=for-the-badge&logo=github)](https://github.com/danielrosehill/Cloud-ASR-MCP)

---

### OR Audio Transcription MCP

Open Router-based audio transcription MCP server.

[![View Repo](https://img.shields.io/badge/View_Repo-GitHub-181717?style=for-the-badge&logo=github)](https://github.com/danielrosehill/OR-Audio-Transcription-MCP)

---

## Evaluations & Benchmarks

### Whisper Fine Tune Accuracy Eval

Comparing Whisper fine-tunes versus stock Whisper on local inference.

[![View Repo](https://img.shields.io/badge/View_Repo-GitHub-181717?style=for-the-badge&logo=github)](https://github.com/danielrosehill/Whisper-Fine-Tune-Accuracy-Eval)

---

### Whisper WPM Background Noise Eval

Quick eval to answer: how much does speaking pace affect WER/accuracy in ASR?

[![View Repo](https://img.shields.io/badge/View_Repo-GitHub-181717?style=for-the-badge&logo=github)](https://github.com/danielrosehill/Whisper-WPM-Background-Noise-Eval)

---

### Transcription Cleanup Eval

Evaluating various cloud audio understanding models on the transcribe-and-cleanup workflow.

[![View Repo](https://img.shields.io/badge/View_Repo-GitHub-181717?style=for-the-badge&logo=github)](https://github.com/danielrosehill/Transcription-Cleanup-Eval-1225)

---

### One Shot Transcription Microphone Eval

Test samples for various microphones with an STT accuracy evaluation.

[![View Repo](https://img.shields.io/badge/View_Repo-GitHub-181717?style=for-the-badge&logo=github)](https://github.com/danielrosehill/One-Shot-Transcription-Microphone-Eval)

---

### Local ASR STT Benchmark

Quick evaluation to find the best STT model in Speech Note (Ubuntu) for local hardware.

[![View Repo](https://img.shields.io/badge/View_Repo-GitHub-181717?style=for-the-badge&logo=github)](https://github.com/danielrosehill/Local-ASR-STT-Benchmark)

---

### Whisper WPM Test

Whisper words-per-minute testing.

[![View Repo](https://img.shields.io/badge/View_Repo-GitHub-181717?style=for-the-badge&logo=github)](https://github.com/danielrosehill/Whisper-WPM-Test)

---

### Gemini 3.1 Lite Audio Understanding Eval

Evaluation of Gemini 3.1 Lite on audio understanding tasks.

[![View Repo](https://img.shields.io/badge/View_Repo-GitHub-181717?style=for-the-badge&logo=github)](https://github.com/danielrosehill/Gemini-31-Lite-Audio-Understanding-Eval)

---

### Voice Cleanup Prompt Experiment

Testing various permutations in system prompting for raw audio transcript cleanup and comparing multimodal ASR vs. the STT + LLM approach.

[![View Repo](https://img.shields.io/badge/View_Repo-GitHub-181717?style=for-the-badge&logo=github)](https://github.com/danielrosehill/Voice-Cleanup-Prompt-Experiment)

---

## Whisper Fine-Tuning & Setup

### Whisper Finetune V2

Whisper fine-tuning iteration.

[![View Repo](https://img.shields.io/badge/View_Repo-GitHub-181717?style=for-the-badge&logo=github)](https://github.com/danielrosehill/Whisper-Finetune-V2)

---

### Modal Whisper Finetune Script

Validated fine-tuning script for fine-tuning Whisper on Modal GPU with a preformatted audio dataset.

[![View Repo](https://img.shields.io/badge/View_Repo-GitHub-181717?style=for-the-badge&logo=github)](https://github.com/danielrosehill/Modal-Whisper-Finetune-Script)

---

### Whisper Fine Tuning Data

Whisper fine-tuning dataset.

[![View Repo](https://img.shields.io/badge/View_Repo-GitHub-181717?style=for-the-badge&logo=github)](https://github.com/danielrosehill/Whisper-Fine-Tuning-Data)

---

### Whisper Fine Tune 171125

Whisper fine-tuning iteration.

[![View Repo](https://img.shields.io/badge/View_Repo-GitHub-181717?style=for-the-badge&logo=github)](https://github.com/danielrosehill/Whisper-Fine-Tune-171125)

---

### Whisper Base FUTO

Whisper base model via FUTO.

[![View Repo](https://img.shields.io/badge/View_Repo-GitHub-181717?style=for-the-badge&logo=github)](https://github.com/danielrosehill/Whisper-Base-FUTO)

---

### Local STT Fine Tune Tests

Local STT fine-tuning tests.

[![View Repo](https://img.shields.io/badge/View_Repo-GitHub-181717?style=for-the-badge&logo=github)](https://github.com/danielrosehill/Local-STT-Fine-Tune-Tests)

---

### Fine Tuned STT Formats

Fine-tuned STT data formats.

[![View Repo](https://img.shields.io/badge/View_Repo-GitHub-181717?style=for-the-badge&logo=github)](https://github.com/danielrosehill/Fine-Tuned-STT-Formats)

---

### whisper-cpp-rocm-setup

whisper.cpp ROCm setup scripts.

[![View Repo](https://img.shields.io/badge/View_Repo-GitHub-181717?style=for-the-badge&logo=github)](https://github.com/danielrosehill/whisper-cpp-rocm-setup)

---

### Whisper Local Notes

Notes on local Whisper usage.

[![View Repo](https://img.shields.io/badge/View_Repo-GitHub-181717?style=for-the-badge&logo=github)](https://github.com/danielrosehill/Whisper-Local-Notes)

---

## ASR Training Data

### ASR Training Data Collector

GUI to facilitate gathering training data for ASR/STT apps in organised datasets with audio capture, text capture, and JSONL metadata construction. Supports LLM-generated text and user-provided.

[![View Repo](https://img.shields.io/badge/View_Repo-GitHub-181717?style=for-the-badge&logo=github)](https://github.com/danielrosehill/ASR-Training-Data-Collector)

---

### ASR Training Data Collector GUI Template

GUI template for ASR training data collection.

[![View Repo](https://img.shields.io/badge/View_Repo-GitHub-181717?style=for-the-badge&logo=github)](https://github.com/danielrosehill/ASR-Training-Data-Collector-GUI-Template)

---

### ASR Training Data Chunker

Breaks up texts by approximate reading duration for ASR training.

[![View Repo](https://img.shields.io/badge/View_Repo-GitHub-181717?style=for-the-badge&logo=github)](https://github.com/danielrosehill/ASR-Training-Data-Chunker)

---

## Other Utilities

### Readiness Voice Agent

Voice agent implementation for readiness checklists.

[![View Repo](https://img.shields.io/badge/View_Repo-GitHub-181717?style=for-the-badge&logo=github)](https://github.com/danielrosehill/Readiness-Voice-Agent)

---

### Voice Note Classification Model

Model for classifying voice notes.

[![View Repo](https://img.shields.io/badge/View_Repo-GitHub-181717?style=for-the-badge&logo=github)](https://github.com/danielrosehill/Voice-Note-Classification-Model)

---

### Voice Note Classifier Model

Voice note classifier model.

[![View Repo](https://img.shields.io/badge/View_Repo-GitHub-181717?style=for-the-badge&logo=github)](https://github.com/danielrosehill/Voice-Note-Classifier-Model)

---

### Voice Note Dataset

Frontend for open source voice note dataset for annotation/classification project.

[![View Repo](https://img.shields.io/badge/View_Repo-GitHub-181717?style=for-the-badge&logo=github)](https://github.com/danielrosehill/Voice-Note-Dataset)

---

### Voice Note Ragie Pipeline

Test pipeline: voice context data to Ragie.

[![View Repo](https://img.shields.io/badge/View_Repo-GitHub-181717?style=for-the-badge&logo=github)](https://github.com/danielrosehill/Voice-Note-Ragie-Pipeline)

---

### Voice Prompt Cleanup Script

Audio processing cleanup script.

[![View Repo](https://img.shields.io/badge/View_Repo-GitHub-181717?style=for-the-badge&logo=github)](https://github.com/danielrosehill/Voice-Prompt-Cleanup-Script)

---

### Dictation Macropad

Plan/key allocation for a macropad optimised for heavy daily dictation workflows.

[![View Repo](https://img.shields.io/badge/View_Repo-GitHub-181717?style=for-the-badge&logo=github)](https://github.com/danielrosehill/Dictation-Macropad)

---

### Voicepad

Planning notes for a macropad for STT users.

[![View Repo](https://img.shields.io/badge/View_Repo-GitHub-181717?style=for-the-badge&logo=github)](https://github.com/danielrosehill/Voicepad)

---

### Voice Headset Design

Voice headset design notes.

[![View Repo](https://img.shields.io/badge/View_Repo-GitHub-181717?style=for-the-badge&logo=github)](https://github.com/danielrosehill/Voice-Headset-Design)

---

### Dictation Microphones

Dictation microphone notes and comparisons.

[![View Repo](https://img.shields.io/badge/View_Repo-GitHub-181717?style=for-the-badge&logo=github)](https://github.com/danielrosehill/Dictation-Microphones)

---

### Hebrish Whisper Tester

Testing Whisper with Hebrew-English mixed speech.

[![View Repo](https://img.shields.io/badge/View_Repo-GitHub-181717?style=for-the-badge&logo=github)](https://github.com/danielrosehill/Hebrish-Whisper-Tester)

---

## Notes & Ideas

### VoiceBox

Concept for a speech tech solution — specced out by Claude.

[![View Repo](https://img.shields.io/badge/View_Repo-GitHub-181717?style=for-the-badge&logo=github)](https://github.com/danielrosehill/VoiceBox)

---

### Live Typing UX Research

Claude-assisted technical research into live voice typing implementation approaches — streaming inference patterns, partial-result handling, turn detection, and UX tradeoffs for at-cursor dictation.

[![View Repo](https://img.shields.io/badge/View_Repo-GitHub-181717?style=for-the-badge&logo=github)](https://github.com/danielrosehill/Live-Typing-UX-Research)

---

### Linux Voice Typing App Notes

Planning notes for a Linux voice typing tool.

[![View Repo](https://img.shields.io/badge/View_Repo-GitHub-181717?style=for-the-badge&logo=github)](https://github.com/danielrosehill/Linux-Voice-Typing-App-Notes)

---

### Speech To Text Chain Notes

Notes on STT processing chain for future voice projects.

[![View Repo](https://img.shields.io/badge/View_Repo-GitHub-181717?style=for-the-badge&logo=github)](https://github.com/danielrosehill/Speech-To-Text-Chain-Notes)

---

### Cloud STT Price Points

Point-in-time pricing snapshots for ASR services.

[![View Repo](https://img.shields.io/badge/View_Repo-GitHub-181717?style=for-the-badge&logo=github)](https://github.com/danielrosehill/Cloud-STT-Price-Points-1225)

---

### ASR And STT AI Notebook

Prompts and outputs on STT, ASR, and fine-tuning with Claude.

[![View Repo](https://img.shields.io/badge/View_Repo-GitHub-181717?style=for-the-badge&logo=github)](https://github.com/danielrosehill/ASR-And-STT-AI-Notebook)

---

### Linux Friendly Voice Tech

List of resources for voice technology with Linux support, encompassing STT, ASR, and dev frameworks.

[![View Repo](https://img.shields.io/badge/View_Repo-GitHub-181717?style=for-the-badge&logo=github)](https://github.com/danielrosehill/Linux-Friendly-Voice-Tech)

---

### Voice Control Linux

Claude-enhanced research for voice control platforms with Linux support.

[![View Repo](https://img.shields.io/badge/View_Repo-GitHub-181717?style=for-the-badge&logo=github)](https://github.com/danielrosehill/Voice-Control-Linux)

---

### voice-typing-collection

Collection of voice typing / STT GitHub repos for testing on Linux.

[![View Repo](https://img.shields.io/badge/View_Repo-GitHub-181717?style=for-the-badge&logo=github)](https://github.com/danielrosehill/voice-typing-collection)

---

### Awesome Whisper Apps

Useful speech-to-text tools that use Whisper under the hood (API/local).

[![View Repo](https://img.shields.io/badge/View_Repo-GitHub-181717?style=for-the-badge&logo=github)](https://github.com/danielrosehill/Awesome-Whisper-Apps)

---

### STT TTS Train 1125

STT and TTS training notes.

[![View Repo](https://img.shields.io/badge/View_Repo-GitHub-181717?style=for-the-badge&logo=github)](https://github.com/danielrosehill/STT-TTS-Train-1125)
