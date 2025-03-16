We introduce STORY2GAME, a novel approach to
using Large Language Models to generate text-based interactive
fiction games that starts by generating a story, generates and
populates the world and, generates the code for actions in a
game engine that enable the story to play out interactively.
Whereas a given set of hard-coded actions can artificially
constrain story generation, the ability to generate actions means
the story generation process can be more open-ended but still
allow for experiences that are grounded in a game state. The
key to successful action generation is to use LLM-generated
preconditions and effects of actions in the stories as guides for
what aspects of the game state must be tracked and changed
by the game engine when a player performs an action. We also
introduce a technique for dynamically generating new actions
to accommodate the player’s desire to perform actions that
they think of that are not part of the story. Dynamic action
generation may require on-the-fly updates the game engine’s state
representation and revision of previously generated actions. We
evaluate the success rate of action code generation with respect
to whether a player can interactively play through the an entire
generated story.
