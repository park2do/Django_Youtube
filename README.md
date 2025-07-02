# Django_Youtube

## (1) Project Settings

- Github

## Model 구조 -> ORM

(1) User

- email
- password
- nickname
- is_business

(2) video

- thumbnail
- link
- view_count
- title
- video_file
- description

=> S3 bucket 활용 (링크)

(3) Reaction

- User: FK
- Video: FK
- reaction (like, dislike, cancel)

(4) Comment

- User
- Video
- Content
- like
- dislike

(5) Subscription

- User: FK (Subscriber)
- User: FK (Subscriber_to)

(6) Common_Model

- Created_at
- updated_at
