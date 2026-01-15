# silprograms-Workflow_Post_Functions-HRGROUPSECURITY.sil
Скрипт для Post Function.  Смысл скрипта такой: При создании запроса вместе с ним создается группа во внутреннем хранилище. В неё добавляются пользователь из полей Technical Experts и SMD. Для того, чтобы группа поддерживалась в актуальном состоянии необходимо отслеживать изменение этих полей и затем обновлять группу. Для этого в SIL Listeners мы добавляем этот скрипт. Он будет прослушивать его и триггерить скрипт. Далее HR в резюме в специальном поле, куда можно добавлять группы, будет добавлять сототвествующие группы из вакансий (руками или через селфтранзижен, пока не решил) и таким образом добавлять к просмотру запроса Резюме новых пользователей.

16509 with the ID of “User Picker (single user)” field. Single user picker with the name of “SMD” field.

16510 with the ID of “User Picker (multiple users)” field. Multi user picker with the name of “Technical Experts” field.

17602 with the ID of “Permission Group” field.
