# Csci166 Baseline-DQN DDQN Final Project
## Original Base Code Pong Notebook
[Frogger](https://github.com/jozeni00/csci166_deep_q_learning/blob/main/Frogger_DQN_Complete_Project.ipynb)
## Frogger Docs
[frogger_documentation](https://ale.farama.org/environments/frogger/)

<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto">Gameplay Videos</h2><a id="user-content-gameplay-videos" class="anchor" aria-label="Permalink: Gameplay Videos" href="#gameplay-videos"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto">🕹️ DQN Donkey Kong Agent Evaluation</h2><a id="user-content-️-dqn-donkey-kong-agent-evaluation" class="anchor" aria-label="Permalink: 🕹️ DQN Donkey Kong Agent Evaluation" href="#️-dqn-donkey-kong-agent-evaluation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto">Baseline Agent (DQN)</h3><a id="user-content-baseline-agent-dqn" class="anchor" aria-label="Permalink: Baseline Agent (DQN)" href="#baseline-agent-dqn"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<markdown-accessiblity-table data-catalyst=""><table>
<thead>
<tr>
<th>Episode</th>
<th>Avg Reward</th>
<th>Preview</th>
<th>Video</th>
</tr>
</thead>
<tbody>
<tr>
<td>Randomish</td>
<td>~200</td>
<td><a target="_blank" rel="noopener noreferrer" href="/Bat4E/Csci166-RL-DQN-Final-Project/blob/main/dk_thumbnail.png"><img src="/Bat4E/Csci166-RL-DQN-Final-Project/raw/main/dk_thumbnail.png" width="120" style="max-width: 100%;"></a></td>
<td><a href="https://bat4e.github.io/Csci166-RL-DQN-Final-Project/base_start-dk.mp4" rel="nofollow">▶ Watch</a></td>
</tr>
<tr>
<td>MidPoint</td>
<td>~1200</td>
<td><a target="_blank" rel="noopener noreferrer" href="/Bat4E/Csci166-RL-DQN-Final-Project/blob/main/dk_thumbnail.png"><img src="/Bat4E/Csci166-RL-DQN-Final-Project/raw/main/dk_thumbnail.png" width="120" style="max-width: 100%;"></a></td>
<td><a href="https://bat4e.github.io/Csci166-RL-DQN-Final-Project/base_mid-dk.mp4" rel="nofollow">▶ Watch</a></td>
</tr>
<tr>
<td>Endpoint</td>
<td>~1650</td>
<td><a target="_blank" rel="noopener noreferrer" href="/Bat4E/Csci166-RL-DQN-Final-Project/blob/main/dk_thumbnail.png"><img src="/Bat4E/Csci166-RL-DQN-Final-Project/raw/main/dk_thumbnail.png" width="120" style="max-width: 100%;"></a></td>
<td><a href="https://bat4e.github.io/Csci166-RL-DQN-Final-Project/base_end-dk.mp4" rel="nofollow">▶ Watch</a></td>
</tr>
</tbody>
</table></markdown-accessiblity-table>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto">Variant Agent (Double + Dueling + PER)</h3><a id="user-content-variant-agent-double--dueling--per" class="anchor" aria-label="Permalink: Variant Agent (Double + Dueling + PER)" href="#variant-agent-double--dueling--per"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<markdown-accessiblity-table data-catalyst=""><table>
<thead>
<tr>
<th>Episode</th>
<th>Avg Reward</th>
<th>Preview</th>
<th>Video</th>
</tr>
</thead>
<tbody>
<tr>
<td>Start/Midpoint</td>
<td>~1400 (spikes to 2200)</td>
<td><a target="_blank" rel="noopener noreferrer" href="/Bat4E/Csci166-RL-DQN-Final-Project/blob/main/dk_thumbnail.png"><img src="/Bat4E/Csci166-RL-DQN-Final-Project/raw/main/dk_thumbnail.png" width="120" style="max-width: 100%;"></a></td>
<td><a href="https://bat4e.github.io/Csci166-RL-DQN-Final-Project/variant_start-dk.mp4" rel="nofollow">▶ Watch</a></td>
</tr>
<tr>
<td>End/Learned</td>
<td>~1300–1400 (volatile)</td>
<td><a target="_blank" rel="noopener noreferrer" href="/Bat4E/Csci166-RL-DQN-Final-Project/blob/main/dk_thumbnail.png"><img src="/Bat4E/Csci166-RL-DQN-Final-Project/raw/main/dk_thumbnail.png" width="120" style="max-width: 100%;"></a></td>
<td><a href="https://bat4e.github.io/Csci166-RL-DQN-Final-Project/variant_end-dk.mp4" rel="nofollow">▶ Watch</a></td>
</tr>
</tbody>
</table></markdown-accessiblity-table>
</article></div>
