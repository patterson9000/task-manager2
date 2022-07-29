# task-manager2
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.1/css/all.min.css
   "
    />
    <link rel="stylesheet" href="./style/mystyle.css" />
    <title>Document</title>
  </head>
  <body>
    <h1>Task manager</h1>
    <main class="main-container">
      <section class="sec-list">
        <h3>list</h3>

        <div>
          <button type="button" id="formButton">
            hide
        </button>
        </div>

      </section>

      <section class="sec-form">
        <h3>Task information</h3>

        <div class-="my-control">
          <lable>important</lable>
          <i id="iImportant" class="fa-solid fa-exclamation"></i>
        </div>

        <div class="my-control">
          <label>title</label>
          <input type="text" />
        </div>

        <div class="my-control">
          <lable>description</lable>
          <textarea row="3"></textarea>
        </div>

        <div class-="my-control">
          <lable>due date</lable>
          <input type="datetime-local" />
        </div>

        <div class-="my-control">
          <lable>color</lable>
          <input type="color" />
        </div>

        <div class-="my-control">
          <lable>emoji</lable>
          <input type="text" />
        </div>

        <div class-="my-control">
          <lable>location</lable>
          <input type="text" />
        </div>

        <div class="my-control">
          <lable>status</lable>
          <select>
            <option>new</option>
            <option>in progress</option>
            <option>blocked</option>
            <option>paused</option>
            <option>removed</option>
            <option>done</option>
          </select>
        </div>

        <div class-="my-control">
          <lable>notification</lable>
          <input type="checkbox" />
        </div>
      </section>
    </main>

    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.6.0/jquery.min.js"></script>
    <script src="./script/main.js"></script>
  </body>
</html>

<!--
    important
    title
    dueDate
    description
    color
    emoji
    location
    status
    notification
    reminder
-->
