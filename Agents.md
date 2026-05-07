# YouTube Comment Question Extractor

The **YouTube Comment Question Extractor** analyzes YouTube comments on given video URLs to extract questions. These can be used by content creators to brainstorm new content ideas based on audience inquiries.

## How It Works:
1. Fetches comments from YouTube videos via the YouTube Data API.
2. Uses regular expressions to extract sentences structured as questions.
3. Stores extracted questions, commenter info, and other metadata for analysis.

## Inputs:
- `videoUrls`: List of YouTube video URLs to scrape.
- `maxComments`: Limit the number of comments to process per video.

## Outputs:
- `videoUrl`: The URL of the video.
- `commenter`: Username of the commenter.
- `commentText`: Full text of the comment.
- `questionText`: The extracted question(s).
- `timestamp`: Time the data was processed.

## Use Cases:
- Help creators understand their audience's inquiries.
- Identify frequently asked questions (FAQs) for a specific topic.
- Stay aligned with trending or audience-requested content themes.
