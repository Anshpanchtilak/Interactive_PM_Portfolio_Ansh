<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>README: Ansh Panchtilak - Interactive Portfolio</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        body {
            font-family: ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, "Noto Sans", sans-serif;
            line-height: 1.6;
        }
        .container {
            max-width: 800px;
        }
        .section-header {
            border-bottom: 2px solid #C66B3D;
        }
        .tag {
            background-color: #4A7C78;
            color: white;
        }
        .note {
            border-left: 4px solid #C66B3D;
        }
    </style>
</head>
<body class="bg-white p-6 md:p-10">

    <div class="container mx-auto">
        <header class="text-center mb-10">
            <h1 class="text-4xl font-extrabold text-[#333]">Interactive Product Portfolio</h1>
            <p class="text-xl text-gray-600 mt-2">Demonstrating a blend of Engineering and Product Management skills.</p>
        </header>

        <section class="mb-8">
            <h2 class="text-2xl font-bold section-header pb-2 mb-4 text-[#C66B3D]">🚀 Project Goal</h2>
            <p class="text-gray-700">
                To move beyond a traditional, static resume by presenting professional data in an interactive dashboard format. This approach showcases not only the **technical ability to build** but also the **strategic mindset** to organize, visualize, and prioritize product information.
            </p>
        </section>

        <section class="mb-8">
            <h2 class="text-2xl font-bold section-header pb-2 mb-4 text-[#C66B3D]">💡 Product Philosophy (Why a Dashboard?)</h2>
            <div class="bg-gray-50 p-4 rounded-lg note">
                <p class="text-sm text-gray-800">
                    The chosen **Dashboard Layout** simulates a real-world product management or BI (Business Intelligence) tool. It allows a reviewer (the "user") to quickly access key metrics and data points (Experience, Skills, Projects) instead of scanning long paragraphs.
                </p>
                <ul class="list-disc ml-6 mt-2 text-sm text-gray-700">
                    <li>**Navigation:** Sidebar acts as a **feature list**.</li>
                    <li>**Metrics:** Charts (Doughnut, Radar) make **quantitative impact** (e.g., +20% efficiency) instantly visible.</li>
                    <li>**Strategy:** The Project toggle demonstrates the ability to articulate **"Why" (Product View)** and **"How" (Tech View)**.</li>
                </ul>
            </div>
        </section>

        <section class="mb-8">
            <h2 class="text-2xl font-bold section-header pb-2 mb-4 text-[#C66B3D]">🛠️ Technology Stack</h2>
            <ul class="space-y-3">
                <li class="flex items-start">
                    <span class="tag px-3 py-1 rounded text-xs font-semibold mr-3 mt-1">HTML5 / JavaScript</span>
                    <span class="text-gray-700">Core structure and the entire routing/data logic (all contained in a single HTML file for portability).</span>
                </li>
                <li class="flex items-start">
                    <span class="tag px-3 py-1 rounded text-xs font-semibold mr-3 mt-1">Tailwind CSS</span>
                    <span class="text-gray-700">Used for utility-first styling, ensuring a clean, modern, and responsive UI/UX.</span>
                </li>
                <li class="flex items-start">
                    <span class="tag px-3 py-1 rounded text-xs font-semibold mr-3 mt-1">Chart.js Library</span>
                    <span class="text-gray-700">Utilized to create the **Doughnut Charts** (for quantitative impact) and the **Radar Chart** (for the balanced competency matrix).</span>
                </li>
            </ul>
        </section>

        <section class="mb-8">
            <h2 class="text-2xl font-bold section-header pb-2 mb-4 text-[#C66B3D]">✨ Key Interactive Features</h2>
            <div class="space-y-4">
                <div class="bg-white p-4 rounded-lg shadow-sm border border-gray-200">
                    <h3 class="font-bold text-lg text-[#4A7C78]">Project View Toggle (Product vs. Tech)</h3>
                    <p class="text-gray-600 text-sm mt-1">In the 'Projects & Strategy' section, users can toggle the content of each project card between:</p>
                    <ul class="list-disc ml-6 mt-2 text-sm text-gray-600">
                        <li>**Product View:** Focuses on the **Problem, Solution, and Business Impact**.</li>
                        <li>**Tech View:** Focuses on the **Architecture, Frameworks, and Technical Implementation**.</li>
                    </ul>
                </div>
                <div class="bg-white p-4 rounded-lg shadow-sm border border-gray-200">
                    <h3 class="font-bold text-lg text-[#4A7C78]">Dynamic Data Visualization</h3>
                    <p class="text-gray-600 text-sm mt-1">Charts dynamically render upon navigation to the 'Experience & Impact' and 'Competency Matrix' sections, clearly illustrating:</p>
                    <ul class="list-disc ml-6 mt-2 text-sm text-gray-600">
                        <li>Metrics from the Full Stack Internship (e.g., <span class="font-bold">20% efficiency gain</span>).</li>
                        <li>A balanced profile shape across **Product Strategy, AI/ML, and Core Engineering**.</li>
                    </ul>
                </div>
            </div>
        </section>

        <footer class="mt-10 text-center text-gray-500 text-sm border-t pt-4">
            <p>This portfolio is a single-page application built using pure client-side code (HTML, JS, CSS Frameworks).</p>
        </footer>
    </div>

</body>
</html>
