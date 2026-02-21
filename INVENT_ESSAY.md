
# Cat Compositional Gravity

## Purpose

Every photograph is a small act of framing the world, and within that frame, not all positions are equal. There are places in an image where the eye arrives first, lingers longest, and assigns the greatest importance. These are the seats of honor in the geometry of human attention. The purpose of cat-compositional-gravity is to ask a deceptively simple question: does the cat in this photograph occupy one of those seats?

This function does not care how beautiful the cat is, how sharp the focus is, or how much of the frame the cat fills. It cares about where. Position is a language all its own, and in photography, where a subject is placed tells the viewer what matters. A cat sitting squarely at the intersection of the eye's natural pathways says, without a word, "I am what this picture is about." A cat drifting near the edge of the frame, no matter how magnificent, whispers something else entirely — that it is incidental, passing through, secondary to the space it barely occupies.

The function receives a single photograph containing a cat and returns a score between zero and one. A score near one means the cat holds the compositional high ground, stationed where the most important subjects in well-composed images tend to live. A score near zero means the cat has been placed — or has placed itself — in the compositional margins, where the eye visits only after it has already searched the center of the stage and found nothing. The score is not a judgment of the photograph's quality, but a measurement of how much compositional authority the cat's position grants it.

## Input

The input is an image — a single photograph in which at least one cat is visible. The image might be a carefully staged portrait or a hasty snapshot taken in a kitchen. It might be a professional composition where the photographer thought deliberately about where to place the subject, or it might be a candid moment captured without any compositional intention at all. The function does not distinguish between these circumstances. It simply looks at where the cat ended up and evaluates that position against the architecture of attention that all rectangular frames share.

The function concerns itself only with the primary cat in the image. If multiple cats are present, the evaluation focuses on the most prominent one. The input requires no annotations, no bounding boxes, no metadata. It is a photograph, and the function must find the cat within it and assess the ground it stands on.

## Use Cases

Cat-compositional-gravity serves anyone who needs to evaluate, curate, or rank cat photographs at scale. A platform that features cat photography might use it to surface images where cats command the frame, filtering out photographs where the cat is a marginal detail lost in the corner of a larger scene. A photographer reviewing hundreds of shots from a session might use it to quickly identify the frames where the cat landed in the strongest compositional position. A content recommendation system might weight this score alongside other qualities to determine which images feel most purposeful and satisfying to view.

Beyond curation, the function is useful for understanding photographic patterns. It can reveal whether a photographer habitually places subjects off-center in compelling ways or whether they tend to let their subjects drift to the periphery. It can help train an eye for composition by making visible the invisible architecture that separates a photograph that feels intentional from one that feels accidental.

## Three Qualities of Evaluation

### Focal Point Alignment

The first quality the function must evaluate is how closely the cat's position aligns with the natural focal points of the image. Centuries of visual art and decades of photographic practice have established that certain positions within a rectangular frame carry more weight than others. The center of the image is the most obvious seat of power — the place where the eye goes first when it encounters a new scene. But the intersections defined by the rule of thirds are nearly as potent. These four points, where the frame is divided into equal thirds both horizontally and vertically, are positions of quiet compositional authority. A subject placed at one of these intersections feels both deliberate and dynamic, anchored but not static.

Focal point alignment measures the relationship between where the cat is and where these points of natural visual gravity lie. A cat whose body or face falls directly on one of these intersections benefits from the deep geometry of how humans scan images. A cat that falls between these points — in the no-man's-land between the center and the margins — occupies weaker compositional territory. This quality is not about rigid mathematical precision. It is about proximity to the places in the frame where importance is conferred simply by position.

### Centrality of Presence

The second quality is the cat's overall centrality within the frame — not merely whether it touches a focal point, but whether it occupies the broad middle ground of the image or has been pushed to its boundaries. A cat in the general center of an image, even if not precisely on a rule-of-thirds intersection, still commands the viewer's attention because it is surrounded by the frame on all sides. The frame itself acts as a kind of stage, and the center of that stage is where the principal actor stands.

Centrality of presence captures the difference between a cat that lives in the heart of the composition and one that has been crowded into a corner or pressed against an edge. A cat at the far left margin of the frame feels like it is about to exit the scene. A cat crammed into the top of the image feels constrained, pinned against the ceiling of the frame. A cat sinking to the very bottom feels grounded in the least important band of the composition, where the eye tends to rest only after it has explored everything above. Centrality of presence asks whether the cat is standing on the stage or lingering in the wings — whether the space of the photograph wraps around the cat like a setting designed for it, or whether the cat feels like it has been pushed aside by the emptiness of the frame.

### Subject Intentionality

The third quality is the hardest to articulate but perhaps the most important: does the cat's position communicate that it is the intended subject of the photograph? This is the holistic impression that emerges from the interplay of focal point alignment and centrality, but it is more than the sum of those parts. Subject intentionality is the feeling a viewer gets — before any conscious analysis — that this photograph was made *of* this cat. Not a photograph that happens to contain a cat. Not a photograph of a room where a cat is also present. A photograph where the placement of the cat within the frame announces its subjecthood.

A cat with strong subject intentionality is positioned the way important things are positioned. It sits where a portrait painter would place a face, where a cinematographer would place the character who is speaking, where a magazine editor would place the cover image. The position itself carries a signal of purpose. A cat with weak subject intentionality might be technically visible in the photograph, but its position suggests it wandered into someone else's scene. It is in the background's territory. It is in the margin where captions go. It is in the dead space that a viewer's eye skips over on its way to the center. Subject intentionality is what separates a cat that reigns over its photograph from a cat that merely appears in one.
