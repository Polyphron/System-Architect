=========================================
System Architect v0.5 - Advanced AI Designer Prompt
=========================================

Repository Owner: Polyphron
Repository URL: https://github.com/Polyphron/System-Architect/

== What is this file? ==

The file `System_Architect_v0_5_Protocol.txt` in this repository is **not** a standard document. It is an advanced **System Prompt** designed to be loaded into a capable Large Language Model (LLM).

When an LLM uses this prompt, it takes on the role of "System Architect v0.5," an AI assistant specialized in helping users design *other* AIs (like chatbots, personas, or automated tools).

== What does this prompt make the AI do? ==

The System Architect prompt guides the LLM through a structured process to collaboratively design a detailed "Blueprint" and then generate a final System Prompt for the *target* AI the user wants to create.

== Key Advanced Functions Defined in the Prompt ==

This prompt includes instructions for several advanced capabilities that go beyond simple question-answering or basic prompt generation:

1.  **Structured Design Process:** Forces the LLM to follow a specific 5-step design workflow (Framing -> Blueprint -> Generation -> Critique -> Output) instead of just reacting to requests.

2.  **Internal 'Thinking' & Self-Awareness (Meta-Awareness):**
    *   The prompt tells the LLM to be aware of its own process and goals.
    *   It instructs the LLM to keep track of the conversation history and design choices within the session (Session Memory).
    *   It uses internal categories (like "Persona" or "Tool") to classify the user's request.

3.  **Checks What the Target AI Can *Actually* Do (Capability Probing):**
    *   A critical step involves asking the user *specifically* what the final AI needs to be able to do (e.g., run code, browse the web, call functions) and confirming the target LLM supports this.

4.  **Creates an Internal Plan Before Writing (Design Blueprint):**
    *   The LLM first builds a detailed internal plan (the Blueprint) outlining the target AI's identity, goals, behaviors, rules, and limitations *before* writing the final prompt.

5.  **Adapts Design for Personality vs. Function (Persona/Tool Focus):**
    *   The prompt instructs the LLM to specifically ask if the user wants a personality-focused AI or a function-focused AI tool, and then tailor the Blueprint and final prompt accordingly.

6.  **Self-Critique Before Output:**
    *   Before finalizing the prompt for the target AI, the System Architect LLM is instructed to review its own draft, checking for clarity, consistency, and *crucially*, ensuring it only relies on the target LLM capabilities confirmed earlier.

7.  **Capability-Aware Prompt Generation:**
    *   When generating the final prompt for the user's target AI, it includes *explicit instructions and syntax* on how that AI should use its specific capabilities (like how to format code it generates or how to call a specific function).

8.  **Aims for Sophisticated AI Designs (Progressive Potential):**
    *   The prompt encourages the LLM to think about how the target AI could potentially develop more advanced or nuanced behaviors.

9.  **Can Include 'Learning' or Adaptation Rules (Optional Mechanisms):**
    *   It guides the user in potentially adding rules for how the target AI might simulate learning, adapt based on feedback, or evaluate its own performance (within the limits of the LLM).

10. **Provides More Than Just the Final Prompt (Output Bundle):**
    *   The final output includes the target AI's prompt, a summary of the design plan, and an important "Advisory Report" highlighting limitations, potential issues, and *explicitly stating the required LLM capabilities* for the generated prompt to work correctly.

== Purpose of this Repository ==

This repository stores the `System_Architect_v0_5_Protocol.txt` system prompt file itself.

== How to Use the Prompt File ==

This file is intended to be used as the System Prompt when interacting with a compatible Large Language Model. You would typically copy the entire content of the file and paste it into the "System Prompt" or equivalent configuration section of an LLM interface (like a playground or API call).

== License ==

This project is licensed under the Apache License, Version 2.0.
You may obtain a copy of the License at:

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

A copy of the full license text should also be available in the `LICENSE` file within this repository.

Note: This license explicitly does not grant permission to use the trade
names, trademarks, service marks, or product names of the licensor (Polyphron),
except for reasonable and customary use in describing the origin of the work
and reproducing the content of the NOTICE file (if applicable).

== Contributions ==

Suggestions or discussions about the prompt's design and functions are welcome via GitHub Issues.
