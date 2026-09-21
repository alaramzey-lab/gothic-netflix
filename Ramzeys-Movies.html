<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ramzey's movies</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Cinzel+Decorative:wght@400;700&family=Cinzel:wght@400;700&display=swap" rel="stylesheet">
    <style>
        :root {
            --bg-color: #0a0a0a;
            --accent-color: #8b0000;
            --accent-glow: #ff1a1a;
            --text-color: #e0e0e0;
            --card-width: 200px;
            --card-height: 280px;
        }

        * { box-sizing: border-box; margin: 0; padding: 0; }

        body {
            background-color: var(--bg-color);
            color: var(--text-color);
            font-family: 'Cinzel', serif;
            min-height: 100vh;
            overflow-x: hidden;
            padding-bottom: 50px;
        }

        header {
            text-align: center;
            padding: 40px 20px 20px 20px;
            border-bottom: 2px solid var(--accent-color);
            box-shadow: 0 5px 20px rgba(139, 0, 0, 0.3);
            background: linear-gradient(180deg, #150000 0%, #0a0a0a 100%);
            position: relative;
        }

        .main-title {
            font-family: 'Cinzel Decorative', serif;
            font-size: 3.5rem;
            color: var(--accent-color);
            text-shadow: 0 0 10px var(--accent-glow), 2px 2px 4px #000;
            outline: none;
            display: inline-block;
            border-bottom: 1px dashed transparent;
            transition: border-color 0.3s;
            padding: 5px 15px;
        }

        .main-title:focus {
            border-color: var(--accent-glow);
            background: rgba(255,255,255,0.02);
        }

        .subtitle {
            font-size: 0.9rem;
            letter-spacing: 4px;
            color: #888;
            margin-top: 10px;
            text-transform: uppercase;
        }

        .mode-badge {
            position: absolute;
            top: 15px;
            right: 20px;
            font-size: 0.7rem;
            letter-spacing: 1px;
            color: #888;
            border: 1px solid #333;
            padding: 4px 10px;
            border-radius: 3px;
        }

        .container {
            max-width: 1400px;
            margin: 0 auto;
            padding: 40px 20px;
        }

        .movie-section { margin-bottom: 50px; }

        .section-title {
            font-family: 'Cinzel Decorative', serif;
            font-size: 1.8rem;
            margin-bottom: 20px;
            color: #fff;
            border-left: 4px solid var(--accent-color);
            padding-left: 15px;
            text-shadow: 0 0 5px rgba(139, 0, 0, 0.5);
            display: flex;
            align-items: center;
            justify-content: space-between;
            flex-wrap: wrap;
            gap: 10px;
        }

        .section-actions {
            display: flex;
            gap: 10px;
            flex-wrap: wrap;
        }

        .netflix-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(var(--card-width), 1fr));
            gap: 25px;
        }

        .movie-card {
            width: 100%;
            height: var(--card-height);
            background: #111;
            border: 1px solid #222;
            border-radius: 4px;
            position: relative;
            cursor: pointer;
            overflow: hidden;
            transition: transform 0.4s cubic-bezier(0.25, 1, 0.5, 1), border-color 0.4s;
            box-shadow: 0 4px 10px rgba(0,0,0,0.7);
        }

        .movie-card:hover {
            transform: scale(1.08);
            border-color: var(--accent-glow);
            box-shadow: 0 10px 25px rgba(139, 0, 0, 0.4);
            z-index: 2;
        }

        .card-dropzone {
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            text-align: center;
            padding: 20px;
            border: 2px dashed #444;
        }

        .card-dropzone:hover, .card-dropzone.dragover {
            border-color: var(--accent-glow);
            background: rgba(139, 0, 0, 0.05);
        }

        .drop-icon {
            font-size: 2.5rem;
            color: #555;
            margin-bottom: 10px;
            transition: color 0.3s;
        }

        .movie-card:hover .drop-icon { color: var(--accent-color); }

        .drop-text {
            font-size: 0.8rem;
            color: #888;
            text-transform: uppercase;
            letter-spacing: 1px;
        }

        .poster-thumb {
            width: 100%;
            height: 100%;
            display: flex;
            align-items: center;
            justify-content: center;
            background: linear-gradient(135deg, #1a0000 0%, #050505 100%);
            position: relative;
        }

        .poster-thumb::before {
            content: '▶';
            font-size: 3rem;
            color: rgba(255, 255, 255, 0.15);
            transition: color 0.3s, transform 0.3s;
        }

        .movie-card:hover .poster-thumb::before {
            color: var(--accent-glow);
            transform: scale(1.2);
        }

        .public-badge {
            position: absolute;
            top: 8px;
            left: 8px;
            background: rgba(139, 0, 0, 0.9);
            color: #fff;
            font-size: 0.65rem;
            padding: 3px 8px;
            border-radius: 3px;
            letter-spacing: 1px;
            text-transform: uppercase;
            z-index: 4;
        }

        .card-metadata {
            position: absolute;
            bottom: 0;
            left: 0;
            width: 100%;
            background: linear-gradient(0deg, rgba(0,0,0,0.95) 0%, rgba(0,0,0,0.7) 70%, rgba(0,0,0,0) 100%);
            padding: 15px 10px 10px 10px;
        }

        .card-title-input {
            width: 100%;
            background: transparent;
            border: none;
            border-bottom: 1px dashed transparent;
            color: #fff;
            font-family: 'Cinzel', serif;
            font-size: 0.95rem;
            font-weight: bold;
            outline: none;
            text-overflow: ellipsis;
            white-space: nowrap;
            overflow: hidden;
        }

        .card-title-input:focus {
            border-color: var(--accent-glow);
            white-space: normal;
            overflow: visible;
        }

        .card-actions {
            position: absolute;
            top: 8px;
            right: 8px;
            display: flex;
            gap: 5px;
            opacity: 0;
            transition: opacity 0.3s;
            z-index: 5;
        }

        .movie-card:hover .card-actions { opacity: 1; }

        .btn-mini {
            background: rgba(0,0,0,0.8);
            border: 1px solid #444;
            color: #aaa;
            width: 24px;
            height: 24px;
            border-radius: 50%;
            cursor: pointer;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 0.8rem;
            transition: all 0.3s;
        }

        .btn-mini:hover {
            border-color: var(--accent-glow);
            color: #fff;
            background: var(--accent-color);
        }

        .theater-overlay {
            position: fixed;
            top: 0; left: 0;
            width: 100%; height: 100%;
            background: rgba(5, 5, 5, 0.98);
            z-index: 100;
            display: none;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            padding: 40px;
            animation: fadeIn 0.3s ease-out forwards;
        }

        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }

        .theater-container {
            width: 100%;
            max-width: 1100px;
            background: #000;
            border: 2px solid var(--accent-color);
            box-shadow: 0 0 50px rgba(139, 0, 0, 0.6);
            position: relative;
            border-radius: 4px;
            overflow: hidden;
        }

        .theater-header {
            background: #111;
            padding: 15px 25px;
            border-bottom: 1px solid #222;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .theater-title {
            font-family: 'Cinzel Decorative', serif;
            color: #fff;
            font-size: 1.4rem;
            text-shadow: 0 0 5px var(--accent-glow);
        }

        .close-theater {
            background: transparent;
            border: none;
            color: #888;
            font-size: 2rem;
            cursor: pointer;
            transition: color 0.3s;
            line-height: 1;
        }

        .close-theater:hover { color: var(--accent-glow); }

        .video-wrapper {
            position: relative;
            padding-top: 56.25%;
            background: #000;
        }

        .video-wrapper video {
            position: absolute;
            top: 0; left: 0;
            width: 100%; height: 100%;
            outline: none;
        }

        .controls-panel {
            display: flex;
            justify-content: center;
            gap: 15px;
            margin-top: 30px;
            flex-wrap: wrap;
        }

        .btn-gothic {
            background: linear-gradient(180deg, #4a0000 0%, #220000 100%);
            border: 1px solid var(--accent-color);
            color: var(--text-color);
            font-family: 'Cinzel', serif;
            font-size: 0.95rem;
            padding: 12px 24px;
            cursor: pointer;
            letter-spacing: 2px;
            text-transform: uppercase;
            box-shadow: 0 0 10px rgba(139, 0, 0, 0.3);
            transition: all 0.3s;
            border-radius: 4px;
        }

        .btn-gothic:hover {
            border-color: var(--accent-glow);
            box-shadow: 0 0 20px var(--accent-glow);
            background: linear-gradient(180deg, #6a0000 0%, #330000 100%);
            color: #fff;
        }

        .btn-gothic.secondary {
            background: linear-gradient(180deg, #1a1a1a 0%, #0a0a0a 100%);
            border-color: #444;
        }

        .btn-gothic.secondary:hover {
            border-color: var(--accent-glow);
            background: linear-gradient(180deg, #2a0000 0%, #110000 100%);
        }

        .toast {
            position: fixed;
            bottom: 30px;
            left: 50%;
            transform: translateX(-50%) translateY(100px);
            background: #1a0000;
            border: 1px solid var(--accent-color);
            color: #fff;
            padding: 14px 28px;
            border-radius: 4px;
            font-size: 0.95rem;
            letter-spacing: 1px;
            z-index: 200;
            opacity: 0;
            transition: all 0.4s cubic-bezier(0.25, 1, 0.5, 1);
            box-shadow: 0 0 20px rgba(139, 0, 0, 0.5);
            max-width: 90%;
            text-align: center;
        }

        .toast.show {
            transform: translateX(-50%) translateY(0);
            opacity: 1;
        }

        .empty-public {
            grid-column: 1 / -1;
            text-align: center;
            padding: 60px 20px;
            color: #666;
            border: 1px dashed #333;
            border-radius: 4px;
        }

        .empty-public p {
            margin-top: 10px;
            font-size: 0.9rem;
            letter-spacing: 1px;
        }

        #publicFileInput, #privateFileInput { display: none; }

        @media (max-width: 600px) {
            .main-title { font-size: 2.2rem; }
            .mode-badge { position: static; margin-top: 12px; display: inline-block; }
        }
    </style>
</head>
<body>

    <header>
        <h1 class="main-title" id="siteTitle" contenteditable="true" onblur="saveSiteTitle()">Ramzey's movies</h1>
        <div class="subtitle">Your Eternal Cinematic Vault</div>
        <div class="mode-badge">Fully Offline</div>
    </header>

    <div class="container">
        <!-- PRIVATE VAULT -->
        <div class="movie-section">
            <h2 class="section-title">
                <span>My Dark Vault</span>
                <div class="section-actions">
                    <button class="btn-gothic secondary" onclick="createNewSlot()" style="padding: 8px 16px; font-size: 0.8rem;">+ Summon Card</button>
                    <button class="btn-gothic" onclick="shareEntireVault()" style="padding: 8px 16px; font-size: 0.8rem;">☁ Share Vault</button>
                </div>
            </h2>
            <div class="netflix-grid" id="movieGrid"></div>
        </div>

        <!-- PUBLIC SECTION (local) -->
        <div class="movie-section">
            <h2 class="section-title">
                <span>Public Movies</span>
                <div class="section-actions">
                    <button class="btn-gothic" onclick="document.getElementById('publicFileInput').click()" style="padding: 8px 16px; font-size: 0.8rem;">↑ Upload Public</button>
                    <button class="btn-gothic secondary" onclick="clearPublicVault()" style="padding: 8px 16px; font-size: 0.8rem;">Clear All</button>
                </div>
            </h2>
            <div class="netflix-grid" id="publicGrid">
                <div class="empty-public" id="publicEmpty">
                    <div style="font-size: 2rem; margin-bottom: 10px;">⌀</div>
                    <p>No public films yet. Share from your vault or upload here.</p>
                </div>
            </div>
        </div>

        <div class="controls-panel">
            <button class="btn-gothic secondary" onclick="createNewSlot()">+ Summon Movie Card</button>
            <button class="btn-gothic" onclick="shareEntireVault()">☁ Share My Vault to Public</button>
        </div>
    </div>

    <input type="file" id="publicFileInput" accept="video/*" onchange="handlePublicFileSelect(event)">
    <input type="file" id="privateFileInput" accept="video/*" multiple style="display:none">

    <!-- Theater -->
    <div class="theater-overlay" id="theaterOverlay">
        <div class="theater-container">
            <div class="theater-header">
                <div class="theater-title" id="theaterTitle">Now Screening</div>
                <button class="close-theater" onclick="closeTheater()">&times;</button>
            </div>
            <div class="video-wrapper">
                <video id="mainPlayer" controls autoplay></video>
            </div>
        </div>
    </div>

    <div class="toast" id="toast"></div>

    <script>
        let db = null;
        const DB_NAME = "GothicNetflixDB";
        const DB_VERSION = 2;
        const STORE_PRIVATE = "movies";
        const STORE_PUBLIC = "publicMovies";
        const STORE_SETTINGS = "settings";

        function showToast(msg, duration = 3200) {
            const t = document.getElementById('toast');
            t.textContent = msg;
            t.classList.add('show');
            setTimeout(() => t.classList.remove('show'), duration);
        }

        function escapeHtml(str) {
            if (!str) return '';
            return String(str)
                .replace(/&/g, '&amp;')
                .replace(/"/g, '&quot;')
                .replace(/'/g, '&#39;')
                .replace(/</g, '&lt;')
                .replace(/>/g, '&gt;');
        }

        // ========== INDEXEDDB ==========
        function initDB() {
            const request = indexedDB.open(DB_NAME, DB_VERSION);

            request.onerror = (e) => console.error("DB error:", e.target.errorCode);

            request.onupgradeneeded = (event) => {
                const activeDB = event.target.result;
                if (!activeDB.objectStoreNames.contains(STORE_PRIVATE)) {
                    activeDB.createObjectStore(STORE_PRIVATE, { keyPath: "id" });
                }
                if (!activeDB.objectStoreNames.contains(STORE_PUBLIC)) {
                    activeDB.createObjectStore(STORE_PUBLIC, { keyPath: "id" });
                }
                if (!activeDB.objectStoreNames.contains(STORE_SETTINGS)) {
                    activeDB.createObjectStore(STORE_SETTINGS, { keyPath: "key" });
                }
            };

            request.onsuccess = (event) => {
                db = event.target.result;
                loadSiteSettings();
                loadPrivateCatalog();
                loadPublicCatalog();
            };
        }

        function saveSiteTitle() {
            const titleEl = document.getElementById("siteTitle");
            const tx = db.transaction(STORE_SETTINGS, "readwrite");
            tx.objectStore(STORE_SETTINGS).put({ key: "title", value: titleEl.innerText });
        }

        function loadSiteSettings() {
            const tx = db.transaction(STORE_SETTINGS, "readonly");
            const req = tx.objectStore(STORE_SETTINGS).get("title");
            req.onsuccess = () => {
                if (req.result) document.getElementById("siteTitle").innerText = req.result.value;
            };
        }

        // ========== PRIVATE VAULT ==========
        function loadPrivateCatalog() {
            const grid = document.getElementById("movieGrid");
            grid.innerHTML = "";

            const tx = db.transaction(STORE_PRIVATE, "readonly");
            const req = tx.objectStore(STORE_PRIVATE).getAll();

            req.onsuccess = () => {
                const items = req.result;
                if (items.length === 0) {
                    for (let i = 0; i < 8; i++) generateBlankSlot(i);
                    return;
                }
                items.sort((a, b) => a.id - b.id);
                items.forEach(renderPrivateCard);
            };
        }

        function generateBlankSlot(idValue) {
            const tx = db.transaction(STORE_PRIVATE, "readwrite");
            const movie = { id: idValue, title: `Dark Selection ${idValue + 1}`, hasVideo: false, videoBlob: null };
            tx.objectStore(STORE_PRIVATE).put(movie);
            tx.oncomplete = () => renderPrivateCard(movie);
        }

        function createNewSlot() {
            const tx = db.transaction(STORE_PRIVATE, "readonly");
            const req = tx.objectStore(STORE_PRIVATE).getAll();
            req.onsuccess = () => {
                let maxId = -1;
                req.result.forEach(item => { if (item.id > maxId) maxId = item.id; });
                generateBlankSlot(maxId + 1);
            };
        }

        function renderPrivateCard(movie) {
            const grid = document.getElementById("movieGrid");
            const card = document.createElement("div");
            card.className = "movie-card";
            card.id = `private-${movie.id}`;

            if (!movie.hasVideo) {
                card.classList.add("card-dropzone");
                card.innerHTML = `
                    <div class="drop-icon">⌽</div>
                    <div class="drop-text">Drag Video Here</div>
                    <div class="card-metadata">
                        <input type="text" class="card-title-input" value="${escapeHtml(movie.title)}"
                               onclick="event.stopPropagation();"
                               onchange="updatePrivateTitle(${movie.id}, this.value)">
                    </div>
                    <div class="card-actions">
                        <button class="btn-mini" onclick="event.stopPropagation(); deletePrivate(${movie.id})">&times;</button>
                    </div>
                `;
                card.addEventListener("dragover", e => { e.preventDefault(); card.classList.add("dragover"); });
                card.addEventListener("dragleave", () => card.classList.remove("dragover"));
                card.addEventListener("drop", e => {
                    e.preventDefault();
                    card.classList.remove("dragover");
                    const files = e.dataTransfer.files;
                    if (files.length && files[0].type.startsWith("video/")) {
                        commitPrivateVideo(movie.id, files[0]);
                    }
                });
            } else {
                card.innerHTML = `
                    <div class="poster-thumb" onclick="launchPrivateCinema(${movie.id})"></div>
                    <div class="card-metadata">
                        <input type="text" class="card-title-input" value="${escapeHtml(movie.title)}"
                               onclick="event.stopPropagation();"
                               onchange="updatePrivateTitle(${movie.id}, this.value)">
                    </div>
                    <div class="card-actions">
                        <button class="btn-mini" title="Share to Public" onclick="event.stopPropagation(); shareSingle(${movie.id})">☁</button>
                        <button class="btn-mini" title="Remove video" onclick="event.stopPropagation(); purgePrivateVideo(${movie.id})">⎋</button>
                        <button class="btn-mini" title="Delete card" onclick="event.stopPropagation(); deletePrivate(${movie.id})">&times;</button>
                    </div>
                `;
            }
            grid.appendChild(card);
        }

        function updatePrivateTitle(id, newTitle) {
            const tx = db.transaction(STORE_PRIVATE, "readwrite");
            const store = tx.objectStore(STORE_PRIVATE);
            const req = store.get(id);
            req.onsuccess = () => {
                const data = req.result;
                data.title = newTitle;
                store.put(data);
            };
        }

        function commitPrivateVideo(id, file) {
            const tx = db.transaction(STORE_PRIVATE, "readwrite");
            const store = tx.objectStore(STORE_PRIVATE);
            const req = store.get(id);
            req.onsuccess = () => {
                const data = req.result;
                data.hasVideo = true;
                data.videoBlob = file;
                if (data.title.startsWith("Dark Selection")) {
                    data.title = file.name.replace(/\.[^/.]+$/, "") || file.name;
                }
                store.put(data).onsuccess = () => loadPrivateCatalog();
                store.put(data).onerror = () => showToast("Storage full — try a smaller file");
            };
        }

        function purgePrivateVideo(id) {
            const tx = db.transaction(STORE_PRIVATE, "readwrite");
            const store = tx.objectStore(STORE_PRIVATE);
            const req = store.get(id);
            req.onsuccess = () => {
                const data = req.result;
                data.hasVideo = false;
                data.videoBlob = null;
                store.put(data).onsuccess = () => loadPrivateCatalog();
            };
        }

        function deletePrivate(id) {
            const tx = db.transaction(STORE_PRIVATE, "readwrite");
            tx.objectStore(STORE_PRIVATE).delete(id).onsuccess = () => loadPrivateCatalog();
        }

        function launchPrivateCinema(id) {
            const tx = db.transaction(STORE_PRIVATE, "readonly");
            const req = tx.objectStore(STORE_PRIVATE).get(id);
            req.onsuccess = () => {
                const movie = req.result;
                if (movie && movie.hasVideo && movie.videoBlob) {
                    openTheater(movie.title, URL.createObjectURL(movie.videoBlob));
                }
            };
        }

        // ========== PUBLIC SECTION ==========
        function loadPublicCatalog() {
            const grid = document.getElementById("publicGrid");
            const empty = document.getElementById("publicEmpty");

            // remove old cards but keep the empty placeholder
            grid.querySelectorAll(".movie-card").forEach(c => c.remove());

            const tx = db.transaction(STORE_PUBLIC, "readonly");
            const req = tx.objectStore(STORE_PUBLIC).getAll();

            req.onsuccess = () => {
                const items = req.result;
                if (!items.length) {
                    if (empty) empty.style.display = "block";
                    return;
                }
                if (empty) empty.style.display = "none";
                items.sort((a, b) => (b.created || 0) - (a.created || 0));
                items.forEach(renderPublicCard);
            };
        }

        function renderPublicCard(movie) {
            const grid = document.getElementById("publicGrid");
            const card = document.createElement("div");
            card.className = "movie-card";
            card.innerHTML = `
                <div class="public-badge">Public</div>
                <div class="poster-thumb" onclick="launchPublicCinema('${movie.id}')"></div>
                <div class="card-metadata">
                    <input type="text" class="card-title-input" value="${escapeHtml(movie.title)}"
                           onclick="event.stopPropagation();"
                           onchange="updatePublicTitle('${movie.id}', this.value)">
                </div>
                <div class="card-actions">
                    <button class="btn-mini" title="Remove from public" onclick="event.stopPropagation(); deletePublic('${movie.id}')">&times;</button>
                </div>
            `;
            grid.appendChild(card);
        }

        function updatePublicTitle(id, newTitle) {
            const tx = db.transaction(STORE_PUBLIC, "readwrite");
            const store = tx.objectStore(STORE_PUBLIC);
            const req = store.get(id);
            req.onsuccess = () => {
                const data = req.result;
                if (data) {
                    data.title = newTitle;
                    store.put(data);
                }
            };
        }

        function launchPublicCinema(id) {
            const tx = db.transaction(STORE_PUBLIC, "readonly");
            const req = tx.objectStore(STORE_PUBLIC).get(id);
            req.onsuccess = () => {
                const movie = req.result;
                if (movie && movie.videoBlob) {
                    openTheater(movie.title, URL.createObjectURL(movie.videoBlob));
                }
            };
        }

        function deletePublic(id) {
            const tx = db.transaction(STORE_PUBLIC, "readwrite");
            tx.objectStore(STORE_PUBLIC).delete(id).onsuccess = () => {
                loadPublicCatalog();
                showToast("Removed from public");
            };
        }

        function clearPublicVault() {
            if (!confirm("Clear the entire public section?")) return;
            const tx = db.transaction(STORE_PUBLIC, "readwrite");
            tx.objectStore(STORE_PUBLIC).clear().onsuccess = () => {
                loadPublicCatalog();
                showToast("Public vault cleared");
            };
        }

        function handlePublicFileSelect(event) {
            const file = event.target.files[0];
            if (!file) return;
            const title = prompt("Title for this public film:", file.name.replace(/\.[^/.]+$/, "")) || file.name;
            addToPublic(file, title);
            event.target.value = "";
        }

        function addToPublic(file, title) {
            const id = "pub_" + Date.now() + "_" + Math.random().toString(36).slice(2, 8);
            const movie = {
                id,
                title: title || "Untitled",
                videoBlob: file,
                created: Date.now()
            };
            const tx = db.transaction(STORE_PUBLIC, "readwrite");
            tx.objectStore(STORE_PUBLIC).put(movie).onsuccess = () => {
                loadPublicCatalog();
                showToast(`"${title}" added to Public`);
            };
            tx.onerror = () => showToast("Could not save — storage may be full");
        }

        // ========== SHARE ==========
        function shareSingle(id) {
            const tx = db.transaction(STORE_PRIVATE, "readonly");
            const req = tx.objectStore(STORE_PRIVATE).get(id);
            req.onsuccess = () => {
                const movie = req.result;
                if (!movie || !movie.hasVideo || !movie.videoBlob) {
                    showToast("No video on this card");
                    return;
                }
                addToPublic(movie.videoBlob, movie.title);
            };
        }

        function shareEntireVault() {
            const tx = db.transaction(STORE_PRIVATE, "readonly");
            const req = tx.objectStore(STORE_PRIVATE).getAll();
            req.onsuccess = () => {
                const items = req.result.filter(m => m.hasVideo && m.videoBlob);
                if (!items.length) {
                    showToast("No videos in your vault to share");
                    return;
                }
                if (!confirm(`Share ${items.length} movie(s) to the Public section?`)) return;

                let count = 0;
                items.forEach(m => {
                    addToPublic(m.videoBlob, m.title);
                    count++;
                });
                showToast(`Shared ${count} film(s) to Public`);
            };
        }

        // ========== THEATER ==========
        function openTheater(title, url) {
            const overlay = document.getElementById("theaterOverlay");
            const player = document.getElementById("mainPlayer");
            document.getElementById("theaterTitle").innerText = title;
            player.src = url;
            overlay.style.display = "flex";
        }

        function closeTheater() {
            const overlay = document.getElementById("theaterOverlay");
            const player = document.getElementById("mainPlayer");
            if (player.src && player.src.startsWith("blob:")) {
                URL.revokeObjectURL(player.src);
            }
            player.pause();
            player.removeAttribute("src");
            player.load();
            overlay.style.display = "none";
        }

        // ========== BOOT ==========
        window.onload = initDB;
    </script>
</body>
</html>
