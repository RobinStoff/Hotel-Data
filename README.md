Project Structure

The analysis was divided into several sections (Tasks 1–17).

1. Exploring Reservation Patterns
Conditional Formatting

Applied a color scale to reservation counts by:

Reservation status

Lead time category

Arrival month

Insight:

Check-out (kept) reservations are highest during peak months.

Cancellations increase significantly in late summer and early autumn.

No-shows remain relatively low across all months.

Sparklines (Trend Over Year)

Created row-level sparklines to visualize trends for each reservation type.

Insight:

Clear seasonal peaks (summer/early autumn).

Cancellations show stronger volatility than kept reservations.

No-shows remain relatively stable and low.

2. Lead Time Distribution
Histogram – Overall Lead Time

Created a histogram of raw lead time values.

Insight:

Distribution is heavily right-skewed.

Most bookings occur with short to medium lead time.

Long lead times exist but are less frequent.

Histogram – Cancelled vs Kept

Compared lead time distributions for:

Cancelled reservations

Kept reservations

Insight:

Cancelled reservations are more common at longer lead times.

Kept reservations cluster around shorter lead times.

Suggests lead time is related to cancellation probability.

3. Lead Time & Cancellations Relationship
Scatter Plot – Average Lead Time vs Cancellations

Created a scatter plot comparing:

X-axis: Average lead time

Y-axis: Number of cancellations

Insight:

Clear positive correlation.

Higher average lead time tends to correspond with more cancellations.

Relationship is not perfect, suggesting other factors may influence cancellations.

4. Lead Time & Cancellations Over Time

Created a line chart plotting normalized:

Average lead time

Number of cancellations

Insight:

Both metrics follow similar seasonal patterns.

Peaks in lead time often align with peaks in cancellations.

Indicates seasonal demand likely influences both variables.

Important: Correlation does not imply causation — seasonality plays a key role.

5. Distribution Channel Analysis
Average Lead Time by Channel (Bar Chart)

Channels:

Corporate

Direct

Agent

Insight:

Agent bookings have significantly higher average lead time.

Corporate and Direct bookings have shorter planning horizons.

Kept vs Cancelled by Channel (Stacked Bar Chart)

Insight:

Agent channel has the highest total reservation volume.

Agents also have the highest number of cancellations (partly volume-driven).

Cancellation % by Channel & Lead Time (Clustered Column Chart)

Insight:

Long lead times have the highest cancellation rates across all channels.

Agent channel shows the highest cancellation percentages.

Short lead time reservations are far more likely to be kept.

Lead time and distribution channel both influence cancellation behavior.

📊 Tools Used

Conditional Formatting (Color Scales)

Sparklines

Histogram (bin adjustments)

Scatter Plot

Line Charts

Bar Chart

Stacked Bar Chart

Clustered Column Chart

Axis formatting & bin width adjustments

Key Analytical Takeaways

Lead time is positively correlated with cancellations.

Seasonality strongly influences both booking behavior and cancellations.

Distribution channel significantly affects:

Average lead time

Cancellation rates

Agent bookings show higher risk due to longer planning horizon.

Short lead time bookings are more reliable.

What This Project Demonstrates

This project demonstrates:

Ability to select appropriate chart types

Understanding of distribution analysis

Correlation exploration

Seasonal trend analysis

Data storytelling through visualization

Interpretation beyond the chart

Why This Matters

In a business setting, this type of analysis helps:

Improve forecasting

Optimize cancellation policies

Adjust pricing strategies

Manage overbooking risk

Evaluate distribution channel performance
