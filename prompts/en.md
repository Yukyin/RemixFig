# RemixFig: English Prompts

A ChatGPT Plus account with GPT-5.5 access is required. Open a new ChatGPT conversation, upload your figure, then send the following 5 messages one at a time. Wait for GPT to fully respond before sending the next.


**Step 1**

```
Analyze this figure and output the position and attributes of all elements (boxes, text, arrows, icons) as JSON. Use percentage-based coordinates. Do not generate any images or code.
```


**Step 2**

```
Based on the coordinates from the JSON above, recreate this figure as a fully editable PowerPoint. Irregular elements should be preserved as whole units.
```


**Step 3**

```
Generate clean, high-quality versions of all icon elements from the original figure and arrange them on a blank white canvas. Also output the coordinates of each icon in the original figure as a JSON file.
```


**Step 4**

```
Output the position and attributes of each icon in the original figure as JSON. Use percentage-based coordinates. Do not generate any images or code.
```


**Step 5**

```
Now replace the corresponding icons in the generated PPT with the high-quality icons from Step 3, using the precise positions from Step 4. Generate a new fully editable PPT.
```

