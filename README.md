# Call Center Analytics Project

An end-to-end analytics solution for customer support data using Python, pandas, and data visualization tools. This project analyzes Twitter customer support conversations to extract actionable insights for call center operations.

## Overview

This project turns raw Twitter customer support conversations into structured analytics that help improve customer service operations. By analyzing response times, sentiment, issue types, and agent performance, we identify patterns that can enhance customer satisfaction and operational efficiency.

## Technologies Used

- **Python**: Core programming language
- **pandas**: Data processing and analysis
- **matplotlib & seaborn**: Data visualization
- **NLTK & spaCy**: Natural language processing for sentiment analysis and keyword extraction
- **SQL**: Database schema design and query optimization

## Features

- **Conversation Thread Analysis**: Identifies and reconstructs full conversation threads from individual messages
- **Sentiment Analysis**: Measures customer sentiment throughout support interactions
- **Response Time Metrics**: Calculates and visualizes agent response patterns
- **Issue Detection**: Automatically categorizes customer issues by type
- **Agent Performance Tracking**: Measures key agent performance indicators

## Key Findings

Based on the analysis of 50,000 customer support messages across 12,916 conversations:

- Average conversation length: 3.85 messages
- Average response time: 92.37 minutes
- Most common issue type: general inquiries (8,135 conversations)
- Customer satisfaction correlates strongly with response time
- Technical issues take longest to resolve but show highest sentiment improvement
- Top-performing agents maintain high satisfaction scores despite handling complex issues

## Visualizations

The project generates several insightful visualizations:

1. **Response Time Distribution**: Shows how quickly agents respond to customer inquiries
2. **Response Time by Hour**: Identifies peak hours and potential staffing issues
3. **Sentiment by Tweet Type**: Compares sentiment between initial inquiries and responses
4. **Issue Type Distribution**: Breaks down conversation volume by issue category
5. **Resolution Time by Issue**: Shows which issues take longest to resolve
6. **Agent Performance Metrics**: Identifies top-performing agents

## Recommendations

Based on the analysis, we recommend:

1. Focus on reducing response times during peak hours (9-11 AM and 2-4 PM)
2. Provide additional training for agents handling billing issues
3. Implement automated responses for common information requests
4. Monitor sentiment changes as a key performance indicator

## Setup and Usage

1. Clone the repository
2. Install dependencies: `pip install -r requirements.txt`
3. Place the Twitter Customer Support dataset (`twcs.csv`) in the `data/raw` directory
4. Process the data: `python scripts/data_processor.py`
5. Generate analysis: `python scripts/analyze_data.py`
6. View results in the `output` directory

## Future Enhancements

- Real-time analytics dashboard for live monitoring
- Predictive modeling for issue resolution time
- Integration with customer satisfaction surveys
- Automated agent coaching recommendations