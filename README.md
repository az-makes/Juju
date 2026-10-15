# The Julina Atelier

Local portfolio preview: http://127.0.0.1:4177/

To restart, open this folder in a terminal and run `node server.cjs`. Keep it running while viewing. Opening index.html directly does not support the 3D modules or AI endpoint reliably.

Includes light/dark appearance, loader with skip, an actual Three.js gallery with artwork navigation, camera transitions, particles, animated sculpture, guided visit, optional synthesized sound, mouse-following effects, custom arrow and hand cursors, responsive mobile layout, all six work categories (30 images), expandable skills and résumé timeline, original downloadable résumé, contact links, and a portfolio guide.

## Sources
Professional details come from the supplied Julina Marie Urias PDF. Artwork, portrait, portfolio categories and additional creative skills come from https://julinaurias.my.canva.site/pambansangjuju . data.js holds the source content and source Canva template links. No testimonials, completed degrees, rates or client outcomes were invented. The newer résumé's 7+ years replaces the older site's 5+ summary. Assets are local copies of the supplied source site's observed images. Three.js is bundled with its license.

## Remaining limitations
The About presentation animates Julina's actual photo on a curved 3D surface. It is not a realistic rigged human avatar. A faithful animated character requires a separately generated/rigged likeness model and animations. No fabricated likeness was substituted.

The local AI endpoint connects to an existing Ollama service using hermes3:latest. Start Ollama first. Override JULINA_AI_MODEL to use another installed model. First-time model loading can be slow on this computer; a failed request switches to a clearly labeled source-based FAQ. Local AI was verified through the server: it correctly answered that Julina supports English and Spanish. First model loading and prompt processing took several minutes. Publishing this as a static website retains FAQ but requires a hosted backend to offer real AI. Never put provider keys in browser files.

The portfolio has not been publicly published. Contact links open email/phone apps; they do not submit forms or send messages automatically.

## Verification
Desktop and 390px mobile checked in browser: no horizontal overflow, all visible artwork loads, filters show expected collections, collection dialog includes all four ebook samples, appearance toggle, pause control and 3D workspace navigation respond. Both arrow and hand cursor variants and résumé expansion were verified. Local scripts passed syntax checks. preview.jpg is the actual desktop preview.

