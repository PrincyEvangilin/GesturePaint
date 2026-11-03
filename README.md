# 🎨 GesturePaint

GesturePaint is a gesture-controlled painting app that runs in the browser. You can paint with touch, mouse or pen, or draw in the air with your index finger using just your webcam. It is built with plain HTML, CSS and JavaScript, with no frameworks and no build step.

## 📖 About
The idea behind this project is to make digital painting feel natural. Instead of only using a mouse, you can draw with simple hand gestures in front of your camera. The whole app lives in a single file, so it is easy to read, learn from and customise.

## ✨ Features
- 7 brushes: Pen, Calligraphy, Rainbow, Neon glow, Spray, Sparkle and Eraser
- Symmetry / mandala mode (2× to 12×) with a mirror option for instant patterns
- Ink flow: line thickness changes with drawing speed, and pen pressure is supported
- Undo, redo and PNG export
- 10-colour palette with a custom colour picker and adjustable brush size
- Aurora, Night and Paper canvas themes
- Modern glass-style interface that works on desktop and mobile

## 🖐️ Gestures

**Touch**
- Drag to paint
- Two-finger pinch to change brush size
- Two-finger tap to undo
- Three-finger tap to clear the canvas
- Double-tap for the next colour

**Webcam hand tracking**
- ☝️ Index finger only: paint
- ✋ Open palm: move the cursor without painting
- ✌️ Peace sign: next colour
- 🤟 Three fingers: next brush
- ✊ Fist: clear the canvas

## ⚙️ How it works
The app uses the HTML5 Canvas for drawing and the Pointer Events API to handle mouse, touch and pen input in one place. In hand mode, MediaPipe Hands detects 21 landmarks on your hand in real time. The app checks which fingers are extended to recognise each gesture, and smooths the fingertip movement so lines stay clean. Gestures like colour change and clear need to be held for a moment, so they do not trigger by accident.

## 🛠️ Built with
HTML5 Canvas, Vanilla JavaScript, CSS3 and MediaPipe Hands, all in a single HTML file

## 🗺️ Future plans
- Shapes tool
- Layers
- Stroke replay
- Gesture-based brush size control
