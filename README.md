<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Exam Result</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header class="top-bar flex">
        <div class="flex">
            <svg xmlns="http://www.w3.org/2000/svg" width="28" height="28" fill="currentColor" class="bi bi-list" viewBox="0 0 16 16"><path fill-rule="evenodd" d="M2.5 12a.5.5 0 0 1 .5-.5h10a.5.5 0 0 1 0 1H3a.5.5 0 0 1-.5-.5zm0-4a.5.5 0 0 1 .5-.5h10a.5.5 0 0 1 0 1H3a.5.5 0 0 1-.5-.5zm0-4a.5.5 0 0 1 .5-.5h10a.5.5 0 0 1 0 1H3a.5.5 0 0 1-.5-.5z"/></svg>
            <h3 class="logo">Logo</h3>
        </div>
        <div class="flex">
            <div class="profile">
                <svg xmlns="http://www.w3.org/2000/svg" width="32" height="28" fill="currentColor" class="bi bi-person-fill" viewBox="0 0 16 16"><path d="M3 14s-1 0-1-1 1-4 6-4 6 3 6 4-1 1-1 1H3Zm5-6a3 3 0 1 0 0-6 3 3 0 0 0 0 6Z"/></svg>
            </div>
            <h3 class="">Name</h3>
        </div>
    </header>
    <main class="main">
        <nav class="side-bar">
            <div><a href="">Home</a></div>
            <div><a href="">Syllabus</a></div>
            <div><a href="">Modules</a></div>
            <div><a href="">Assignments</a></div>
            <div><a href="">Grades</a></div>
            <div><a href="">Discussion</a></div>
            <div><a href="">People</a></div>
            <div><a href="">Video Conference</a></div>
            <div><a href="">Feedback</a></div>
        </nav>
        <div class="content-bar">
            <div class="content">
                <div class="container">
                    <h3 class="h3">Grade 5/10</h3>
                    <div class="card">
                        <div class="tile flex">
                            <h3 class="quiz">Question 1</h3>
                            <div class="tile-content">
                                <div class="flex qa-section">
                                    <input placeholder="What are the benefits of using https over http?" class="input"/>
                                    <div class="res green">Correct</div>
                                </div>
                                <textarea placeholder="Type your answer here"></textarea>
                            </div>
                       </div>

                       <div class="tile flex">
                            <h3 class="quiz">Question 2</h3>
                            <div class="tile-content">
                                <div class="flex qa-section">
                                    <input placeholder="Which Protocol is used in transport layer?" class="input"/>
                                    <div class="res red">Incorrect</div>
                                </div>
                                <div class="flex check-boxes">
                                    <div class="flex select">
                                        <label for="">Option 1</label>
                                        <input type="checkbox"/>
                                    </div>
                                    <div class="flex select">
                                        <label for="">Option 3</label>
                                        <input type="checkbox"/>
                                    </div>
                                </div>
                                <div class="flex check-boxes">
                                    <div class="flex select">
                                        <label for="">Option 2</label>
                                        <input type="checkbox" checked/>
                                    </div>
                                    <div class="flex select">
                                        <label for="">Option 4</label>
                                        <input type="checkbox"/>
                                    </div>
                                </div>
                            </div>
                        </div>

                        <div class="tile flex">
                            <h3 class="quiz">Question 3</h3>
                            <div class="tile-content">
                                <div class="flex qa-section">
                                    <input placeholder="Is 64-bit IP address used now?" class="input"/>
                                    <div class="res green">Correct</div>
                                </div>
                                <div class="true-false">
                                    <div class="flex choice">
                                        <label for="">True</label>
                                        <input type="checkbox" checked/>
                                    </div>
                                    <div class="flex choice">
                                        <label for="">False</label>
                                        <input type="checkbox"/>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="floating-button">
            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-chat-left-text-fill" viewBox="0 0 16 16">
                <path d="M0 2a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2H4.414a1 1 0 0 0-.707.293L.854 15.146A.5.5 0 0 1 0 14.793V2zm3.5 1a.5.5 0 0 0 0 1h9a.5.5 0 0 0 0-1h-9zm0 2.5a.5.5 0 0 0 0 1h9a.5.5 0 0 0 0-1h-9zm0 2.5a.5.5 0 0 0 0 1h5a.5.5 0 0 0 0-1h-5z"/>
            </svg>
        </div>
    </main>
</body>
</html>
