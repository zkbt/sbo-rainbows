---
name: Visualizing!
about: 'A request for a super swell plot, animation, or other visualization. '
title: 'Visualize [something]. '
labels: learning, visualizing
assignees: ''

---

🧑‍🎨 Please try to make the following visualization, which is important either if it ends up appearing in a paper/talk/proposal or simply if it is for our own personal edification. 🎨

# 🖼️ Plot:
(What is the plot/animation/visualization we're trying to make?)

# 🤔 Motivation: 
(Why?)

# 🧑‍🏫 General Requirements:
1. Consider drawing out a sketch of your plot by hand before coding it up. Think carefully about what you want to show, and why. Use your sketch to inform the final plot you actually make. 
1. Make sure all axes are labeled, using clear language, indicating units, and in a font that is large enough to read if the figure is dropped into a presentation slide. (Often, rather than fussing with individual labels, you can just change the overall size with a `figsize=` keyword to `plt.figure` or `plt.subplots`).
1. If more than one plotting element is included (multiple lines, multiple groups of point), make sure each is clearly labeled. Sometimes a plot legend (with `plt.legend()`) is the clearest way to do this, sometimes locally annotating curves/points requires less cognitive work for the viewer. 
1. If some plotting element should have more visual weight than others, make it so. Line width (`linewidth=`), color (`color=` or `c=`), and opacity (`alpha=`), are often good tools for emphasizing 
1. If multiple panels are included and it makes sense for their axes to be shared, make sure they are shared (like with `plt.subplots(rows, cols, sharex=True/'col', sharey=True/'row')`). If having a specific aspect ratio (such as making equal distances in x and y appear like a square instead of a rectangle) aids interpretation, do it (like with `plt.axis('equal'/'scaled')`).
1. If color is necessary for interpreting your plot, check to make sure the chosen colors are friendly to folks with color-blindness, with help from a tool like [Color Oracle](https://colororacle.org/) and/or a friend.


# 🧑‍💻 Specific Requirements:
1. (What specific details should we emphasize for this specific plot?)

# 🧠 Metacognition:
Plots tell stories. Think about the story you want to tell with your visualization, the story someone viewing it without you nearby, and what work you can do to bring those two into alignment. Early on, paying extra attention to details and interpretability may feel like a waste of time. However, if you try to think of each plot you make as practice in how to clearly, precisely, accurately, honestly, and powerfully convey evidence and scientific information, it will start to feel easier!

# 🎙️ Discuss:
Use this Issue to share drafts, propose revisions, and discuss interpretations of this plot.
