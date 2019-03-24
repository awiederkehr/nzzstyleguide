```html|span-1,no-source,plain
<div class="stabilityIndex stable">Stable</div>
```

## No data, no chart
Often in our line of work, we are asked to recreate charts or complex visualizations based on a static template. In order to design and publish work that meet our quality standards we **only create We only create graphics based on actual data.** Here's why:

#### 1. Using data to make a point – our point
Turning data into a visualization is not neutral. Whoever creates a chart shapes the narrative – by choosing from [dozens of chart types](https://github.com/ft-interactive/chart-doctor/tree/master/visual-vocabulary) and by deciding what to leave out and what to emphasize. We want to control this step rather than use what somebody else has created for their purposes. We can only do that when we have the data.

#### 2. We work digital first
When we have raw data, we are able to create graphics that are fully optimized for our digital platforms. We also have the option to use our own tools, [like Q](https://q.st.nzz.ch/), or write custom code.

#### 3. We want to be able to verify
Without data, we have no way of checking whether the chart correctly represents the underlying data. By using, for example, a static PDF as the only reference, we (unkowningly) reproduce whatever mistakes have been made in creation of the original chart.

#### 4. We need to be exact
Editing somebody else's vector graphics (or even worse: tracing from static images) is much more prone to handling errors than generating our own chart from data.

#### 5. We want our charts to be reusable
Charts based on data can be quickly and efficiently updated or corrected.

#### 6. We don't plagiarize
Sometimes we might have the creator's permission to reproduce their graphics, but often we don't.


## Bylines
Bylines, both in print and online, show the people who contributed a substantial part to the story. Traditionally, bylines were reserved for those who wrote text. Yet, of course, a graphic can be a substantial part of the story, too.

Whenever we contribute a graphic that is essential to the story, we add whoever produced the graphic to the byline. In that case, we remove the «Kürzel» below the graphic.


```image
plain: true
span: 6
src: "assets/guidelines/guidelines-bylines.png"
```



## Pie Charts
Pie charts are popular and often requested by editors. They are, however, rarely the best chart type to visualize what we want to communicate. We use pie charts with caution and whenever we think about using one, we pause to think: **Is this really what makes most sense?**

#### Rule of thumb:
If I combine all segments except for the most important one to "others" – does the chart still make sense?
No? Then don't use a pie chart.

#### Do not

We don't use pie charts to compare the size of various parts of a whole.

```image
plain: true
span: 6
src: "assets/guidelines/guidelines-pie_1@1x.png 1x, assets/guidelines/guidelines-pie_1@2x.png 2x"
```

We don't use pie charts to compare the parts of two or more

```image
plain: true
span: 6
src: "assets/guidelines/guidelines-pie_2@1x.png 1x, assets/guidelines/guidelines-pie_2@2x.png 2x"
```

#### Do

We use pie charts to highlights how small or how large one part of a whole is.
In this case:
- We never show more than 5 segments. Combine to "others" if necessary.
- The segment starts at the top and goes clockwise.

```image
plain: true
span: 6
src: "assets/guidelines/guidelines-pie_3@1x.png 1x, assets/guidelines/guidelines-pie_3@2x.png 2x"
```

See also: [What to consider when creating pie charts (Datawrapper Academy)](https://academy.datawrapper.de/article/127-what-to-consider-when-creating-a-pie-chart)

## Non-zero Y-Axis

Cutting the y-axis so it doesn't extend to 0 is a common way to dramatize a chart, but sometimes it's necessary to show subtle, yet significant changes.

#### Rule of thumb

If the point the chart is supposed to make is visible with the axis extended to 0: don't cut it.

#### Do not

- Never cut the y-axis if the chart uses areas to visually encode values (bars, columns, area charts, etc.).
- Do not cut the y-axis to make a trend appear more dramatic than it is.

```image
plain: true
span: 6
src: "assets/guidelines/guidelines-y-axis_1@1x.png 1x, assets/guidelines/guidelines-y-axis_1@2x.png 2x"
```

- Do not cut the y-axis very close to 0.

```image
plain: true
span: 6
src: "assets/guidelines/guidelines-y-axis_2@1x.png 1x, assets/guidelines/guidelines-y-axis_2@2x.png 2x"
```

#### Do

- Cut the y-axis to show subtle, yet significant changes that wouldn't be visible when the y-axis is extended to zero.
- When cutting an axis, cut sensibly: Leave space above the highest data point and below the lowest data point, but make sure the chart line uses the upper and lower half of the chart.

```image
plain: true
span: 6
src: "assets/guidelines/guidelines-y-axis_5@1x.png 1x, assets/guidelines/guidelines-y-axis_5@2x.png 2x"
```

- Cut the y-axis when extending it to zero doesn't make sense (there are no football players who are 0 metres tall)

```image
plain: true
span: 6
src: "assets/guidelines/guidelines-y-axis_4@1x.png 1x, assets/guidelines/guidelines-y-axis_4@2x.png 2x"
```

For further references and examples see [It’s OK not to start your y-axis at zero (QZ)](https://qz.com/418083/its-ok-not-to-start-your-y-axis-at-zero/)
