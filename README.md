 (cd "$(git rev-parse --show-toplevel)" && git apply --3way <<'EOF' 
diff --git a/README.md b/README.md
index 3be635ecabba511bd21496469afd07e515254b41..eb47340c284a1e6fd094ae1a739fded491736708 100644
--- a/README.md
+++ b/README.md
@@ -1,2 +1,26 @@
-# -1
-网站1
+# Emoji Maker
+
+This repo contains a simple demo page for creating image or text memes.
+
+## Features
+- Upload a local image
+- Add editable text
+- Export the canvas as a PNG file
+
+## Local Preview
+1. Clone the repository and enter the directory:
+   ```bash
+   cd emoji-maker
+   git pull
+   ```
+2. Start a static server:
+   ```bash
+   # Using Node.js
+   npx serve . -p 5173
+   # or using Python
+   python3 -m http.server 5173
+   ```
+3. On Windows, you can simply double-click `index.html` for a quick preview.
+
+Open your browser at `http://localhost:5173` to try the demo.
+
 
EOF
)
