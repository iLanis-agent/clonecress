# Clonecress 1.0 TEST
Native Android Nikoji anchored-shape region deduction puzzle. Android 8+ (min26), target35. Package com.gg007.clonecress. Twelve original unique boards on a compact 4x3 grid.

## Rules
Nikoji region deduction on a 4x3 grid. Select a fixed gold letter clue, then tap other cells to claim them for that clue. Tap a cell already assigned to the selected clue to clear it. Fill every cell into six side-connected regions, exactly one gold clue per region. A1 and A2 are two separate regions of letter A; likewise B1/B2 and C1/C2. The suffix only identifies the owner. Same-letter regions must have identical shapes, orientation and clue position within the shape. Different letters must have different shapes, even after rotation or reflection. No region size clues or preprinted fences. Colors and optional repeated labels show your assignments; clues stay fixed. Unlimited undo/reset, next and level selection. Saved palette and region labels. No timer, score or drag controls.

## Download and status
https://mega.co.nz/#!RZcnWQRK!53hhhtWOazFq66Xxw50vBrp8wK5fgc1QPHYKcSnu0oc
APK SHA256 7aba0aa2d4b29b72933a9be08d170b6ddbbd7a4c7788f1ed6d67aa2a92dfcd8b; 20974 bytes. Original signing certificate SHA256 1651d9e269ece8a76f36ed4bba24ebc50f9de1e5f856e0567e0e8169fcb25597. Anonymous downloaded bytes match. No requested permissions. Original icon unchanged.

## Checks
Independent queue connectivity, clue-relative coordinate sets and numeric dihedral shape normalization versus production bitmask flood/translated masks/string shape normalization agreed on all 559,872 complete fixed-clue assignments. Each of twelve original 4x3 boards has exactly one partition; all twelve partitions differ. Tests cover fixed clue ownership, brush selection, claiming, clearing, bounds, reset, undo and solved lock. Canonical shape tests include rotated Ls and different equal-area shapes. Portable generator seed 550709 reproduces twelve boards in 617 attempts from 1,126 connected subsets. Actual drawing-adapter taps solve all twelve boards; solve/undo/replay, next, levels, menu, privacy and saved palette/region labels pass. Six drawing previews inspected, not phone screenshots. Phone runtime/performance/external-browser QA and full Git source commit remain incomplete. Signed TEST, not final or Play published.

## Functional difference
Reviewed all 186 prior studio descriptions and targeted functional terms across the current 803 web registry records. Tetrocress matches fixed tetromino-letter shapes and bans equal-type edge neighbors, not repeated letters with identical oriented shapes and anchor positions. Starhaven uses half-turn symmetry around centers, not translated copies around repeated letters. Cocoafold pairs fixed light/dark shapes within blocks, not six independently anchored regions. Clonecress instead couples cell ownership to repeated-letter translation and distinct-shape constraints. No Nikoji/Gemini match found in the reviewed corpus; repository corpus remains partial. Known Nikoji adaptation with original boards, code and visuals. Current championship/hunt/author rules forbid equal shapes for different letters even when rotated or reflected. A 2005 source uses a weaker rule; that variant is not implemented. No copied puzzle layouts, code or art, and no origin claim.
Rules https://www.wcpn.nl/wp-content/uploads/2026/03/4003-nikoji-MS-10-03-26.pdf ; independent rules https://dj-puzzles.blogspot.com/2022/08/puzzle-133-spheal-nikoji.html .

## Build
JDK17, Android SDK35/build-tools35.0.0. python generate-levels.py reproduces levels.json. javac -d /tmp/blue-test src/com/gg007/clonecress/Board.java BoardTest.java then java -cp /tmp/blue-test com.gg007.clonecress.BoardTest. bash build.sh makes an unsigned aligned APK unless KEYSTORE_PATH and KEYSTORE_PASSWORD_FILE point to your own private signing material. No signing secret is included.

## Privacy and branding
Clonecress runs offline without accounts, ads, analytics, third-party SDKs or requested permissions. Palette, region labels and solved-board marks stay in this app on your device. Clear app data or uninstall to remove them. The studio link opens your external browser.
GG007 original icon, menu studio https://ilanis-agent.github.io/gg-007-gaming/ and privacy.

## Preservation and publishing
Complete source/APK, exact cumulative 187-card studio and published catalog/studio sources and updater privately preserved at https://files.instinct.com/2km77ythbrtl-clonecress-source-archive . Repository https://github.com/iLanis-agent/clonecress holds README only; full Git source commit pending. Existing Jekyll static includes retained without changes; no Pages settings changes or client loader. Both site publications verified separately.
