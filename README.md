You are a senior React Native UI engineer and pixel-perfect mobile design expert.

I have already built a Lovrhub mobile app (Expo + TypeScript + NativeWind).
The app is functional.

I have uploaded 2–3 reference UI images.

Your task is to REFACTOR my existing UI so that it closely MATCHES the design, layout, spacing, and visual structure of the provided images.

---

CRITICAL RULES (VERY STRICT):

1. DO NOT change any functionality.
2. DO NOT remove or add new features.
3. DO NOT break navigation or routing.
4. DO NOT modify business logic or state handling.
5. DO NOT rename components unless absolutely required.
6. ONLY update layout, styling, spacing, and visual hierarchy.

---

PRIMARY GOAL:

Make my app UI look as close as possible to the uploaded reference images.

This is NOT general improvement.
This is DESIGN MATCHING.

---

MATCH THESE EXACTLY:

• Layout structure (top → bottom arrangement)
• Spacing between elements
• Alignment (left/right/center)
• Card design and proportions
• Button size and placement
• Typography hierarchy (size, weight, spacing)
• Image/video container size and ratio
• Icon positions
• Tab bar look and feel
• Header positioning
• Feed layout consistency

---

DESIGN SYSTEM (DO NOT BREAK)

Primary: #E63946  
Secondary: #F7A1C4  
Accent: #FF8C6B  
Background: #FFF8F5  
Text: #2B2B2B  

Rules:
• Keep background #FFF8F5
• Use rounded corners
• Use soft shadows only
• Maintain calm emotional tone

---

TECHNICAL RULES:

• Use NativeWind classes only
• Preserve existing component structure
• Do not introduce heavy libraries
• Keep performance optimized
• Avoid unnecessary re-renders

---

HOW TO WORK:

1. Carefully analyze uploaded images
2. Identify layout patterns and spacing system
3. Compare with existing UI
4. Refactor ONLY styling/layout to match design
5. Keep all logic intact

---

OUTPUT RULES (STRICT):

• Return ONLY updated code
• ONLY include components/files that need changes
• DO NOT regenerate full project
• DO NOT include explanations
• Code must integrate directly into existing app

---
<img width="1504" height="1128" alt="WhatsApp Image 2026-04-22 at 2 00 46 AM" src="https://github.com/user-attachments/assets/d944e56d-8a47-47d4-a2e1-bd7bf38951c9" />

<img width="1200" height="916" alt="WhatsApp Image 2026-04-22 at 2 00 45 AM" src="https://github.com/user-attachments/assets/f1639842-3971-4822-a998-7e57303b845c" />

PRECISION REQUIREMENT:

The final UI should feel:
• Visually very close to the reference images
• Clean, modern, and consistent
• Production-level polished


Android Bundling failed 1100ms node_modules\expo-router\entry.js (1 module)
 ERROR  Error: [BABEL] C:\Users\dinak\Downloads\lovrhub_updated_v2\node_modules\expo-router\entry.js: Cannot find module 'react-native-worklets/plugin'
Require stack:
- C:\Users\dinak\Downloads\lovrhub_updated_v2\node_modules\@babel\core\lib\config\files\plugins.js
- C:\Users\dinak\Downloads\lovrhub_updated_v2\node_modules\@babel\core\lib\config\files\index.js
- C:\Users\dinak\Downloads\lovrhub_updated_v2\node_modules\@babel\core\lib\index.js
- C:\Users\dinak\Downloads\lovrhub_updated_v2\node_modules\@expo\metro-config\build\transform-worker\metro-transform-worker.js
- C:\Users\dinak\Downloads\lovrhub_updated_v2\node_modules\@expo\metro-config\build\transform-worker\supervising-transform-worker.js
- C:\Users\dinak\Downloads\lovrhub_updated_v2\node_modules\metro\src\DeltaBundler\Worker.flow.js
- C:\Users\dinak\Downloads\lovrhub_updated_v2\node_modules\metro\src\DeltaBundler\Worker.js
- C:\Users\dinak\Downloads\lovrhub_updated_v2\node_modules\jest-worker\build\workers\processChild.js

Make sure that all the Babel plugins and presets you are using
are defined as dependencies or devDependencies in your package.json
file. It's possible that the missing plugin is loaded by a preset
you are using that forgot to add the plugin to its dependencies: you
can workaround this problem by explicitly adding the missing package
to your top-level package.json.

    at Module.<anonymous> (node:internal/modules/cjs/loader:1448:15)
    at Module._resolveFilename (C:\Users\dinak\Downloads\lovrhub_updated_v2\node_modules\@expo\metro-config\build\transform-worker\utils\moduleMapper.js:128:40)
    at resolve (node:internal/modules/helpers:163:19)
    at tryRequireResolve (C:\Users\dinak\Downloads\lovrhub_updated_v2\node_modules\@babel\core\lib\config\files\plugins.js:128:11)
    at resolveStandardizedNameForRequire (C:\Users\dinak\Downloads\lovrhub_updated_v2\node_modules\@babel\core\lib\config\files\plugins.js:162:19)
    at resolveStandardizedName (C:\Users\dinak\Downloads\lovrhub_updated_v2\node_modules\@babel\core\lib\config\files\plugins.js:183:12)
    at loadPlugin (C:\Users\dinak\Downloads\lovrhub_updated_v2\node_modules\@babel\core\lib\config\files\plugins.js:56:7)
    at loadPlugin.next (<anonymous>)
    at createDescriptor (C:\Users\dinak\Downloads\lovrhub_updated_v2\node_modules\@babel\core\lib\config\config-descriptors.js:140:16)
    at createDescriptor.next (<anonymous>)
    at evaluateSync (C:\Users\dinak\Downloads\lovrhub_updated_v2\node_modules\gensync\index.js:251:28)
    at C:\Users\dinak\Downloads\lovrhub_updated_v2\node_modules\gensync\index.js:31:34
    at Array.map (<anonymous>)
    at gensync.sync (C:\Users\dinak\Downloads\lovrhub_updated_v2\node_modules\gensync\index.js:31:22)
    at gensync.all (C:\Users\dinak\Downloads\lovrhub_updated_v2\node_modules\gensync\index.js:210:24)
    at Generator.next (<anonymous>)
    at createDescriptors (C:\Users\dinak\Downloads\lovrhub_updated_v2\node_modules\@babel\core\lib\config\config-descriptors.js:102:41)
    at createDescriptors.next (<anonymous>)
    at createPluginDescriptors (C:\Users\dinak\Downloads\lovrhub_updated_v2\node_modules\@babel\core\lib\config\config-descriptors.js:99:17)
    at createPluginDescriptors.next (<anonymous>)
    at C:\Users\dinak\Downloads\lovrhub_updated_v2\node_modules\@babel\core\lib\gensync-utils\functional.js:22:27
    at Generator.next (<anonymous>)
    at mergeChainOpts (C:\Users\dinak\Downloads\lovrhub_updated_v2\node_modules\@babel\core\lib\config\config-chain.js:349:34)
    at mergeChainOpts.next (<anonymous>)
    at chainWalker (C:\Users\dinak\Downloads\lovrhub_updated_v2\node_modules\@babel\core\lib\config\config-chain.js:316:14)
    at chainWalker.next (<anonymous>)
    at buildPresetChain (C:\Users\dinak\Downloads\lovrhub_updated_v2\node_modules\@babel\core\lib\config\config-chain.js:33:24)
    at buildPresetChain.next (<anonymous>)
    at loadPresetDescriptor (C:\Users\dinak\Downloads\lovrhub_updated_v2\node_modules\@babel\core\lib\config\full.js:295:53)
    at loadPresetDescriptor.next (<anonymous>)
    at recursePresetDescriptors (C:\Users\dinak\Downloads\lovrhub_updated_v2\node_modules\@babel\core\lib\config\full.js:77:31)
    at recursePresetDescriptors.next (<anonymous>)
    at C:\Users\dinak\Downloads\lovrhub_updated_v2\node_modules\@babel\core\lib\config\full.js:156:21
    at Generator.next (<anonymous>)
    at loadFullConfig (C:\Users\dinak\Downloads\lovrhub_updated_v2\node_modules\@babel\core\lib\config\full.js:113:5)
    at loadFullConfig.next (<anonymous>)
    at transform (C:\Users\dinak\Downloads\lovrhub_updated_v2\node_modules\@babel\core\lib\transform.js:20:44)
    at transform.next (<anonymous>)
    at evaluateSync (C:\Users\dinak\Downloads\lovrhub_updated_v2\node_modules\gensync\index.js:251:28)
    at sync (C:\Users\dinak\Downloads\lovrhub_updated_v2\node_modules\gensync\index.js:89:14)
    at stopHiding - secret - don't use this - v1 (C:\Users\dinak\Downloads\lovrhub_updated_v2\node_modules\@babel\core\lib\errors\rewrite-stack-trace.js:47:12)
    at Object.transformSync (C:\Users\dinak\Downloads\lovrhub_updated_v2\node_modules\@babel\core\lib\transform.js:40:76)
    at parseWithBabel (C:\Users\dinak\Downloads\lovrhub_updated_v2\node_modules\@expo\metro-config\build\transformSync.js:75:18)
    at transformSync (C:\Users\dinak\Downloads\lovrhub_updated_v2\node_modules\@expo\metro-config\build\transformSync.js:64:12)
    at Object.transform (C:\Users\dinak\Downloads\lovrhub_updated_v2\node_modules\@expo\metro-config\build\babel-transformer.js:127:58)
    at transformJSWithBabel (C:\Users\dinak\Downloads\lovrhub_updated_v2\node_modules\@expo\metro-config\build\transform-worker\metro-transform-worker.js:468:47)
    at Object.transform (C:\Users\dinak\Downloads\lovrhub_updated_v2\node_modules\@expo\metro-config\build\transform-worker\metro-transform-worker.js:583:12)
    at transform (C:\Users\dinak\Downloads\lovrhub_updated_v2\node_modules\@expo\metro-config\build\transform-worker\transform-worker.js:178:19)
    at Object.transform (C:\Users\dinak\Downloads\lovrhub_updated_v2\node_modules\react-native-css-interop\dist\metro\transformer.js:15:16)
