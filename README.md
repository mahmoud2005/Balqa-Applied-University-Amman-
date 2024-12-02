<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Student Portal</title>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css">
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f0f8ff;
            color: #333;
        }
        header {
            background-color: #004080;
            color: #fff;
            padding: 1rem;
            text-align: center;
        }
        nav a {
            margin: 0 1rem;
            text-decoration: none;
            color: #fff;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .section {
            margin: 2rem auto;
            padding: 1.5rem;
            border: 1px solid #ddd;
            border-radius: 10px;
            background-color: #fff;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        footer {
            background-color: #004080;
            color: white;
            text-align: center;
            padding: 1rem 0;
            margin-top: 2rem;
        }
    </style>
</head>
<body>
    <header>
        <h1>Student Portal</h1>
        <p>Manage your learning with ease</p>
    </header>
    <nav class="text-center p-2" style="background-color: #00509e;">
        <a href="#">Home</a>
        <a href="#">Tests</a>
        <a href="#">Summaries</a>
        <a href="#">Materials</a>
        <a href="#upload">Upload</a>
    </nav>
    <main class="container">
        <div class="section">
            <h2>Tests</h2>
            <p>Find all test-related materials here.</p>
        </div>
        <div class="section">
            <h2>Summaries</h2>
            <p>Access summaries to help you understand the core concepts.</p>
        </div>
        <div class="section">
            <h2>Materials</h2>
            <p>Browse and download additional learning materials.</p>
        </div>
        <div class="section" id="upload">
            <h2>Upload Files</h2>
            <p>If you have valuable materials to share, upload them here. Approval is required before publishing.</p>
            <form action="#" method="POST" enctype="multipart/form-data">
                <div class="mb-3">
                    <label for="file" class="form-label">Choose File</label>
                    <input type="file" class="form-control" id="file" name="file">
                </div>
                <div class="mb-3">
                    <label for="description" class="form-label">File Description</label>
                    <textarea class="form-control" id="description" name="description" rows="3"></textarea>
                </div>
                <button type="submit" class="btn btn-primary">Submit</button>
            </form>
        </div>
    </main>
    <footer>
        &copy; 2024 Student Portal. All rights reserved.
    </footer>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
