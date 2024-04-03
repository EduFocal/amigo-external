All the following endpoints mirror the general amigo endpoints with the exception of
only allowing access to authenticated oauth clients.

Each endpoint mirrors the usage of their normally accessed versions

Please see for directions on how to authenticate with necessary scopes required for each endpoint

### Authentication

https://dev.edufocal.com/docs/01_Authentication/

# Endpoints

### Standards

#### scopes - 'amigo.standard.list'

https://dev.edufocal.com/amigo/teacher/#/operations/get-amigo-api-standard

`GET|HEAD  amigo/api/ext/standard . amigo.ext.standard.standard.list`

https://dev.edufocal.com/amigo/teacher/#/operations/get-amigo-api-standard-exam

`GET|HEAD  amigo/api/ext/standard/exam  amigo.ext.standard.exam.list`

https://dev.edufocal.com/amigo/teacher/#/operations/show-amigo-api-standard-exam-exam_id

`GET|HEAD  amigo/api/ext/standard/exam/{exam_id} amigo.ext.standard.exam.show`

https://dev.edufocal.com/amigo/teacher/#/operations/get-amigo-api-standard-objective

`GET|HEAD  amigo/api/ext/standard/objective . amigo.ext.standard.objective.list`

https://dev.edufocal.com/amigo/teacher/#/operations/show-amigo-api-standard-objective-objective_id

`GET|HEAD  amigo/api/ext/standard/objective/{objective_id} amigo.ext.standard.objective.show`

https://dev.edufocal.com/amigo/teacher/#/operations/get-amigo-api-standard-period

`GET|HEAD  amigo/api/ext/standard/period  amigo.ext.standard.period.list`

https://dev.edufocal.com/amigo/teacher/#/operations/show-amigo-api-standard-period-period_id

`GET|HEAD  amigo/api/ext/standard/period/{period_id} amigo.ext.standard.period.show`

https://dev.edufocal.com/amigo/teacher/#/operations/get-amigo-api-standard-topic

`GET|HEAD  amigo/api/ext/standard/topic . amigo.ext.standard.topic.list`

https://dev.edufocal.com/amigo/teacher/#/operations/show-amigo-api-standard-topic-topic_id

`GET|HEAD  amigo/api/ext/standard/topic/{topic_id} amigo.ext.standard.topic.show`

https://dev.edufocal.com/amigo/teacher/#/operations/show-amigo-api-standard-standard_id

`GET|HEAD  amigo/api/ext/standard/{standard_id} amigo.ext.standard.standard.show`

### course

#### scopes - 'amigo.course.list'

https://dev.edufocal.com/amigo/teacher/#/operations/get-amigo-api-teacher-course

`GET|HEAD  amigo/api/ext/teacher/course amigo.ext.teacher.course.list`

https://dev.edufocal.com/amigo/teacher/#/operations/get-amigo-api-teacher-course-course_id

`GET|HEAD  amigo/api/ext/teacher/course/{course_id} amigo.ext.teacher.course.show`

# file management

#### scopes - 'amigo.course.folder.list'

https://dev.edufocal.com/amigo/teacher/#/operations/listFolders

`GET|HEAD  amigo/api/ext/teacher/course/{course_id}/folders  amigo.ext.teacher.course.folder.index`

https://dev.edufocal.com/amigo/teacher/#/operations/getRootFolder

`GET|HEAD  amigo/api/ext/teacher/course/{course_id}/folders/root amigo.ext.teacher.course.folder.root`

https://dev.edufocal.com/amigo/teacher/#/operations/getFolderByULID

`GET|HEAD  amigo/api/ext/teacher/course/{course_id}/folders/{folder_ulid} amigo.ext.teacher.course.folder.show`

https://dev.edufocal.com/amigo/teacher/#/operations/getFileDetailsByULID

`GET|HEAD  amigo/api/ext/teacher/course/{course_id}/folders/{folder_ulid}/files/{file_ulid} amigo.ext.teacher.course.folder.file.show`

### Quiz

#### scopes - 'amigo.quiz.list'

https://dev.edufocal.com/amigo/teacher/#/operations/list-teacher-quiz

`GET|HEAD  amigo/api/ext/teacher/quiz  amigo.ext.teacher.quiz.list`

https://dev.edufocal.com/amigo/teacher/#/operations/get-quiz-item

`GET|HEAD  amigo/api/ext/teacher/quiz/item  amigo.ext.teacher.quiz.item.show`

https://dev.edufocal.com/amigo/teacher/#/operations/get-teacher-quiz

`GET|HEAD  amigo/api/ext/teacher/quiz/{quiz_id} amigo.ext.teacher.quiz.show`

