# Sentiment-Analysis-of-Product-Reviews
 
 This repo contains sentiment analysis of Amazon Product Reviews
 
 https://nijianmo.github.io/amazon/index.html
 
### Data format
Format is one-review-per-line in json. See examples below for further help reading the data.

### Sample review:
```json
{
"image": ["https://images-na.ssl-images-amazon.com/images/I/71eG75FTJJL._SY88.jpg"], 
"overall": 5.0, 
"vote": "2", 
"verified": True, 
"reviewTime": "01 1, 2018", 
"reviewerID": "AUI6WTTT0QZYS", 
"asin": "5120053084", 
"style": {
	"Size:": "Large", 
	"Color:": "Charcoal"
	}, 
"reviewerName": "Abbey", 
"reviewText": "I now have 4 of the 5 available colors of this shirt... ", 
"summary": "Comfy, flattering, discreet--highly recommended!", 
"unixReviewTime": 1514764800
}
{
  "reviewerID": "A2SUAM1J3GNN3B",
  "asin": "0000013714",
  "reviewerName": "J. McDonald",
  "vote": 5,
  "style": {
    "Format:": "Hardcover"
  },
  "reviewText": "I bought this for my husband who plays the piano.  He is having a wonderful time playing these old hymns.  The music  is at times hard to read because we think the book was published for singing from more than playing from.  Great purchase though!",
  "overall": 5.0,
  "summary": "Heavenly Highway Hymns",
  "unixReviewTime": 1252800000,
  "reviewTime": "09 13, 2009"
}

```

```bash
reviewerID - ID of the reviewer, e.g. A2SUAM1J3GNN3B
asin - ID of the product, e.g. 0000013714
reviewerName - name of the reviewer
vote - helpful votes of the review
style - a disctionary of the product metadata, e.g., "Format" is "Hardcover"
reviewText - text of the review
overall - rating of the product
summary - summary of the review
unixReviewTime - time of the review (unix time)
reviewTime - time of the review (raw)
image - images that users post after they have received the product
```
