/* Import Font & Reset */
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;900&display=swap');
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
body {
    font-family: 'Poppins', sans-serif;
    background: #0d0d0d;
    color: #f4f4f4;
    overflow-x: hidden;
}

/* Hero Section */
.hero {
    height: 100vh;
    background: url('img/hero.jpg') no-repeat center center/cover;
    position: relative;
    display: flex;
    align-items: center;
    justify-content: center;
    overflow: hidden;
}
.hero-overlay {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: linear-gradient(45deg, rgba(255, 59, 0, 0.1), rgba(255, 174, 0, 0.1));
    z-index: 1;
}
#particles-js {
    position: absolute;
    width: 100%;
    height: 100%;
    z-index: 2;
}
.hero-content {
    z-index: 3;
    text-align: center;
    text-shadow: 0 0 20px rgba(255, 59, 0, 0.5), 0 0 40px rgba(255, 174, 0, 0.3);
    filter: drop-shadow(0 0 10px rgba(255, 59, 0, 0.5));
}
.hero h1 {
    font-size: 4rem;
    font-weight: 900;
    margin-bottom: 1rem;
    animation: pulse-glow 3s infinite;
}
.subtitle {
    font-size: 1.5rem;
    font-weight: 300;
    margin-bottom: 2rem;
    opacity: 0;
    animation: fade-up 2s 1s forwards;
}
.play-btn {
    background: #ff3b00;
    color: #f4f4f4;
    border: none;
    padding: 1rem 2rem;
    font-size: 1.2rem;
    font-weight: 600;
    cursor: pointer;
    border-radius: 5px;
    box-shadow: 0 0 20px #ff3b00;
    transition: all 0.3s;
}
.play-btn:hover {
    animation: pulsate 1s infinite;
}
@keyframes pulse-glow {
    0%, 100% { text-shadow: 0 0 20px rgba(255, 59, 0, 0.5); }
    50% { text-shadow: 0 0 40px rgba(255, 174, 0, 0.8); }
}
@keyframes fade-up {
    to { opacity: 1; transform: translateY(0); }
    from { opacity: 0; transform: translateY(20px); }
}
@keyframes pulsate {
    0% { box-shadow: 0 0 20px #ff3b00; }
    50% { box-shadow: 0 0 40px #ffae00; }
    100% { box-shadow: 0 0 20px #ff3b00; }
}

/* Glitch Effects */
.glitch-fast {
    position: relative;
    animation: glitch-fast 0.5s 1s, pulse-glow 3s infinite 1.5s;
}
.glitch-fast::before, .glitch-fast::after {
    content: attr(data-text);
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    color: #ff0000;
    z-index: -1;
    animation: glitch-anim 0.1s infinite;
}
.glitch-light {
    position: relative;
    animation: glitch-light 0.3s;
}
.glitch-light::before {
    content: attr(data-text);
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    color: #ffae00;
    z-index: -1;
    opacity: 0.5;
    animation: glitch-anim 0.2s;
}
@keyframes glitch-fast {
    0%, 100% { transform: translate(0); }
    10% { transform: translate(-2px, 2px); }
    20% { transform: translate(2px, -2px); }
}
@keyframes glitch-anim {
    0% { transform: translate(0); }
    50% { transform: translate(1px, -1px); }
    100% { transform: translate(0); }
}

/* Content Section */
.content {
    padding: 4rem 2rem;
    background: linear-gradient(to bottom, #0d0d0d, #050505);
    position: relative;
}
#content-particles {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    z-index: 1;
}
.content-container {
    max-width: 1200px;
    margin: 0 auto;
    position: relative;
    z-index: 2;
}
.section-header {
    font-size: 2.5rem;
    font-weight: 900;
    margin-bottom: 2rem;
    color: #ffae00;
    text-shadow: 0 0 10px #ff3b00;
}
.content-text {
    font-weight: 400;
    margin-bottom: 3rem;
    line-height: 1.8;
}
.timeline {
    display: flex;
    justify-content: space-between;
    margin-bottom: 3rem;
    position: relative;
}
.timeline::before {
    content: '';
    position: absolute;
    top: 50%;
    left: 0;
    width: 100%;
    height: 2px;
    background: #ff3b00;
    animation: line-grow 2s;
}
.timeline-item {
    background: rgba(255, 59, 0, 0.1);
    padding: 1rem;
    border-radius: 5px;
    flex: 1;
    margin: 0 0.5rem;
    text-align: center;
}
@keyframes line-grow {
    from { width: 0; }
    to { width: 100%; }
}
.bullet-list {
    list-style: none;
    margin-bottom: 3rem;
}
.bullet-list li {
    margin-bottom: 1rem;
    font-weight: 400;
}
.icon {
    margin-right: 0.5rem;
}
.kostum-grid {
    display: flex;
    align-items: center;
    margin-bottom: 3rem;
}
.kostum-img {
    width: 200px;
    height: 150px;
    object-fit: cover;
    margin-right: 1rem;
    transition: transform 0.3s, box-shadow 0.3s;
}
.kostum-img:hover {
    transform: scale(1.05);
    box-shadow: 0 0 20px #ff3b00;
}
.caption {
    font-weight: 300;
    color: rgba(244, 244, 244, 0.82);
}
.fakta-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 1rem;
}
.fakta-item {
    background: rgba(255, 59, 0, 0.1);
    padding: 1rem;
    border-radius: 5px;
    text-align: center;
}

/* Gallery */
.gallery {
    padding: 4rem 2rem;
    background: #0d0d0d;
    text-align: center;
    position: relative;
}
#gallery-particles {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    z-index: 1;
}
.gallery-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 1rem;
    max-width: 1200px;
    margin: 0 auto;
    position: relative;
    z-index: 2;
}
.gallery-img {
    width: 100%;
    height: 250px;
    object-fit: cover;
    border: 2px solid #ff3b00;
    cursor: pointer;
    transition: transform 0.3s, box-shadow 0.3s;
}
.gallery-img:hover {
    transform: scale(1.05);
    box-shadow: 0 0 20px #ffae00;
}
.lightbox {
    display: none;
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: rgba(0, 0, 0, 0.9);
    z-index: 1000;
    align-items: center;
    justify-content: center;
}
.lightbox img {
    max-width: 80%;
    max-height: 80%;
}
.close {
    position: absolute;
    top: 20px;
    right: 30px;
    color: #f4f4f4;
    font-size: 2rem;
    cursor: pointer;
}

/* Maps */
.maps {
    padding: 4rem 2rem;
    background: #050505;
    position: relative;
}
.maps::before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 2px;
    background: linear-gradient(to right, #ff3b00, #ffae00);
}
#maps-particles {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    z-index: 1;
}
.maps-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px