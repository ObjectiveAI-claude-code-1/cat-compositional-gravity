# cat-compositional-gravity

Scores a cat's positional authority within a photograph. Not all positions in an image are equal — the center, the rule-of-thirds intersections, and the broad interior of the frame carry more visual weight than the edges and corners. This function measures whether a cat occupies the compositional ground where the eye expects to find the most important subject, or whether it has been relegated to the margins where secondary elements tend to appear.

## Input

The function accepts a single input:

- **image** *(required)* — A photograph containing at least one cat. No annotations, bounding boxes, or metadata are required. The image can be a professional portrait, a casual snapshot, or anything in between. If multiple cats are present, the evaluation focuses on the most prominent one.

## Output

A scalar score between **0** and **1**:

- **Scores near 1** indicate the cat holds strong positional authority. It is stationed at or near the image's natural focal points, commands the interior of the frame, and its placement communicates clear subjecthood.
- **Scores near 0.5** indicate moderate positional authority. The cat is reasonably placed but does not fully command the compositional high ground — it may sit in a transitional zone between focal points or lean toward a boundary without being pressed against it.
- **Scores near 0** indicate weak positional authority. The cat is pushed to the periphery, pressed against an edge or corner, or positioned in dead space where the eye does not naturally look for the primary subject.

The score is not a judgment of the photograph's overall quality. A stunning photograph may receive a low score if the cat is positioned at the margin, and a mundane snapshot may score high if the cat happens to sit at the compositional center.

## What It Evaluates

The function evaluates three distinct qualities of the cat's position within the frame:

### 1. Focal Point Alignment

How closely the cat's position corresponds to the image's natural points of visual gravity. The center of the frame is the most powerful position — the place where the eye arrives first. The four rule-of-thirds intersections (where the frame is divided into equal thirds horizontally and vertically) are nearly as potent, conferring a sense of deliberate, dynamic placement. This quality measures the proximity between where the cat actually is and where these compositionally powerful positions lie. A cat squarely on a focal point benefits from centuries of visual convention; a cat far from any focal point occupies weaker compositional territory.

### 2. Centrality of Presence

Whether the cat commands the broad middle ground of the image or has been pushed toward its boundaries. This is distinct from focal point alignment — it captures the cat's overall relationship to the edges of the frame rather than its proximity to specific intersections. A cat surrounded by the frame on all sides feels like the principal actor on a stage built for it. A cat pressed against the left margin feels like it is exiting the scene. A cat crammed into the top of the image feels pinned against a ceiling. A cat sinking to the bottom feels grounded in the least important band of the composition. This quality asks whether the photograph wraps around the cat or whether the cat has been crowded aside by empty space.

### 3. Subject Intentionality

The holistic impression of whether the cat's placement communicates that it is the intended subject of the photograph. This is the feeling a viewer gets — before any conscious analysis — that this photograph was made *of* this cat. Not a photograph that happens to contain a cat, and not a photograph of a room where a cat is also present. A cat with strong subject intentionality is positioned the way important things are positioned: where a portrait painter would place a face, where a cinematographer would frame the principal character. A cat with weak subject intentionality may be visible, but its position suggests it wandered into someone else's scene.

## Use Cases

- **Photo curation at scale** — Surface cat photographs where the cat commands the frame, filtering out images where the cat is a marginal detail lost in a corner.
- **Photography review** — Quickly identify the strongest compositional frames from a large session, based on where the cat landed in each shot.
- **Content recommendation** — Weight this score alongside other image qualities to rank photographs that feel purposeful and satisfying to view.
- **Compositional analysis** — Reveal whether a photographer habitually places subjects in strong compositional positions or tends to let them drift to the periphery.
- **Training the eye** — Make visible the invisible architecture of photographic composition by quantifying where the subject sits relative to the frame's natural geometry.
