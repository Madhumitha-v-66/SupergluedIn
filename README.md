# SupergluedIn
The World's Most Inconvenient Professional Network

SUPERGLUEDIN is a deliberately terrible LinkedIn-inspired social networking website created for the UI Gone Bad challenge by Zero Bugs Club. The project takes a normal professional networking platform and intentionally makes every interaction confusing, frustrating, chaotic, and unnecessarily complicated. The goal is not to create broken software, but to create an experience where the user constantly questions what just happened.

The website includes a deliberately horrible authentication system. Users have to deal with an inverted username, backwards password, an on-screen virtual keyboard that rearranges itself, a secret drawing used for authentication, suspicious security warnings, mandatory acknowledgement checkboxes, an evasive login button, and fake verification processes. Despite the intentionally frustrating design, the authentication system remains technically solvable.

SUPERGLUEDIN also features a multi-step CAPTCHA system. Instead of displaying several questions like a normal quiz, one CAPTCHA challenge appears at a time and is replaced by the next challenge after the user responds. Each CAPTCHA session contains between five and ten challenges, and users need at least 75% accuracy to successfully complete the verification. CAPTCHA verification can appear when performing actions such as liking, commenting, reposting, connecting, or sending.

The website intentionally makes simple actions unnecessarily difficult. Action buttons such as LIKE, COMMENT, REPOST, and SEND can rearrange themselves when the user interacts with them. After approximately six or seven interactions, the buttons stop moving and return to their normal order. The website also uses ridiculous confirmation chains where a simple action can require multiple confirmations such as "Are you sure?", "Are you really sure?", and "Confirm final confirmation", only to eventually respond with "Action successfully cancelled."

SUPERGLUEDIN contains other deliberately frustrating interactions, including popup close buttons that try to escape the user's cursor. These buttons move, rotate, or change size, but remain eventually clickable. The website can also occasionally reverse the direction of scrolling for a few seconds without warning, making users wonder whether something is wrong with their mouse or trackpad before returning to normal behavior.

Users can also edit their SUPERGLUEDIN profile. The profile editing system allows users to change information such as their name, username or display name, headline, bio, skills, education, experience, location, and profile picture. The changes are persisted using browser-local storage so that the updated information can remain available after refreshing the page.

The visual design intentionally uses an extremely chaotic style with neon colors, inconsistent spacing, aggressive borders, conflicting typography, oversized and undersized elements, fake alerts, suspicious messages, excessive popups, unnecessary confirmations, and misleading interactions. The overall design philosophy is to make the website confusing, frustrating, annoying, and funny while still remaining technically usable.

The project is built using React, TypeScript, Vite, CSS, LocalStorage, and browser audio/Web Audio APIs. It is primarily a client-side demonstration and parody project and does not require a real authentication backend.

To run the project locally, clone the repository, open the project folder, and run npm install to install the dependencies. Then run npm run dev to start the development server. Vite will provide a local address, usually http://localhost:5173/. For a production build, run npm run build, which generates the production files inside the dist/ folder.

SUPERGLUEDIN is a demo and parody application, so some account and profile information is stored locally in the browser. Clearing the browser's LocalStorage can reset the demo. There is no production authentication system, and users should not enter real passwords or sensitive personal information.

The core philosophy of the project is "Bad UX ≠ Broken Software." The website is supposed to make users think, "WHY IS IT DOING THIS?", but they should eventually be able to complete the important interactions. SUPERGLUEDIN turns friction itself into the main feature.

SUPERGLUEDIN was created for the ZERO BUGS CLUB — UI GONE BAD challenge with the theme "BAD DESIGN. REAL IMPACT. FIX IT. MAKE IT BETTER." The project is a parody inspired by professional social-networking interfaces and is not affiliated with or endorsed by LinkedIn or any other real social-networking platform.
