# Lie Detector AI — Android Test v0.1

This is a UI/logic prototype for an Android app that estimates how suspicious a text statement sounds.

## Current demo
- Text analysis screen
- Heuristic deception-probability score
- Explanation/reasons
- Screenshot analysis placeholder
- History placeholder
- English UI

## Important
The current analyzer is a local demo heuristic. It does NOT prove that someone is lying.

## Build
Open this folder in Android Studio and let Gradle sync. Then run the `app` configuration on an Android emulator/device.

Next production steps:
1. Add OCR for screenshots.
2. Add a real LLM backend for semantic analysis.
3. Analyze full conversations and contradictions.
4. Add Georgian-language analysis.
5. Add secure history and privacy controls.
