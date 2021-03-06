---
layout: default
---

To facilitate communication among stakeholders, software security requirements are typically written in natural language and capture both positive requirements (i.e., what the system is supposed to do to ensure security) and negative requirements (i.e., undesirable behavior undermining security).

Misuse Case Programming (MCP) is an approach that automatically generates security test cases from misuse case specifications (i.e., use case specifications capturing the behavior of malicious users).

MCP tackles the problem of automatically generating executable security test cases from security requirements in natural language (NL). More precisely, since existing approaches for the generation of test cases from NL requirements verify only positive requirements, we focus on the problem of generating test cases from negative requirements.
 
MCP relies on natural language processing techniques to extract the concepts (e.g., inputs and activities) appearing in requirements specifications and generates executable test cases by matching the extracted concepts to the members of a provided test driver API. MCP has been evaluated in an industrial case study, which provides initial evidence of the feasibility and benefits of the approach.

MCP deals with security testing and has been inspired by a previous work developed for functional tetsing, UMTG. The UMTG prototype is available along with demo videos at the following URL https://sites.google.com/site/umtgtestgen/ .

# Demo video

Below, you can watch a video with MCP in action.

{% include youtube.html id=uLIio468jWE %}

# Publications

A paper the describing the MCP tool appears in the companion proceeding of ICSE 2019.

A paper describing MCP has been accepted at ISSRE-2018, the paper is available at http://orbilu.uni.lu/handle/10993/36301.
You can download an archive with the MCP results and the MCP tool from the following URL https://drive.google.com/open?id=17NFzK3wKVPhfXcVGfGN_NcA2yosZFLJt


# Downloads

The up to date version of MCP can be downloaded from Google drive at the following URL: https://drive.google.com/file/d/1mOqecqy7TfIw552lY5OKXePw5VubQBFv/view.

The ISSRE 2018 replicability package is available for download on GitLab https://gitlab.com/SnTsvv/mcp_replicability/.









