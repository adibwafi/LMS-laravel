# LMS-laravel API Documentation

## Models :

_Lessons_

```
- name: string, required
- lesson_pages: JSON, required
- is_completed: integer, required
```

_Quiz_

```
- LessonId: integer, required
- name: string, required
- kkm: integer
- description: string, required
- max attempt: integer
- is_completed: integer, required
```

_QuizPages_

```
- QuizId: integer, required
- name: string, required
- question: JSON, required
```

_QuizPoints_

```
- QuizId: integer, required
- point: integer, required
```

## Endpoints :

List of available endpoints:

- `POST /lesson`
- `GET /lesson`
- `PUT /lesson`
- `DELETE /lesson`

- `POST /quiz`
- `GET /quiz`
- `PUT /quiz`
- `DELETE /quiz`

- `POST /quiz/pages`
- `GET /quiz/pages`
- `DELETE /quiz/pages`

- `GET /quiz/point`
- `POST /quiz/point`
- `DELETE /quiz/point`
- `PUT /quiz/point`

