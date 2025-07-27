<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Navigator Pro. Org - Your Guide to Resources</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Font Awesome for Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css" xintegrity="sha512-Fo3rlrZj/k7ujTnHg4CGR2D7kSs0V4LLanw2qksYuRlEzO+tcaEPQogQ0KaoGN26/zrn20ImR1DfuLWnOo7aBA==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <!-- Google Fonts - Inter -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            -webkit-font-smoothing: antialiased;
            -moz-osx-font-smoothing: grayscale;
            background-color: #f3f4f6; /* Light gray background, kept for subtle contrast */
        }
        /* Custom styles for rounded corners and shadows */
        .card {
            border-radius: 0.75rem; /* Rounded corners for cards */
            box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1), 0 2px 4px -1px rgba(0, 0, 0, 0.06); /* Subtle shadow */
            transition: transform 0.2s ease-in-out;
        }
        .card:hover {
            transform: translateY(-5px); /* Slight lift on hover */
        }
        /* Updated primary button to neon green */
        .btn-primary {
            background-color: #84cc16; /* Lime 500 - Neon Green */
            border-color: #84cc16;
        }
        .btn-primary:hover {
            background-color: #65a30d; /* Lime 600 - Darker Neon Green on hover */
            border-color: #65a30d;
        }
        /* Modal backdrop for overlay */
        .modal-backdrop {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0, 0, 0, 0.5);
            z-index: 999;
            display: none; /* Hidden by default */
        }
        /* Modal content */
        .modal-content {
            background-color: white;
            border-radius: 0.75rem;
            box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1), 0 4px 6px -2px rgba(0, 0, 0, 0.05);
            max-width: 500px;
            width: 90%;
            padding: 1.5rem;
            position: fixed;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            z-index: 1000;
            display: none; /* Hidden by default */
        }
        .modal-header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 1rem;
        }
        .modal-close-btn {
            background: none;
            border: none;
            font-size: 1.5rem;
            cursor: pointer;
            color: #6b7280;
        }
    </style>
</head>
<body class="min-h-screen flex flex-col">

    <!-- Header Section -->
    <header class="bg-lime-500 text-white p-6 shadow-md rounded-b-xl">
        <div class="container mx-auto flex flex-col md:flex-row items-center justify-between">
            <h1 class="text-3xl font-bold mb-2 md:mb-0">Navigator Pro. Org</h1>
            <nav>
                <ul class="flex space-x-4">
                    <li><a href="#about" class="hover:text-lime-200 transition-colors">About Us</a></li>
                    <li><a href="#resources" class="hover:text-lime-200 transition-colors">Resources</a></li>
                    <li><a href="#contact" class="hover:text-lime-200 transition-colors">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <!-- Hero/Mission Statement Section -->
    <section id="about" class="bg-white py-12 px-6 text-center shadow-inner rounded-xl mx-4 my-6">
        <div class="container mx-auto">
            <h2 class="text-4xl font-extrabold text-gray-800 mb-4">Your Reliable Guide Through Life's Challenges</h2>
            <p class="text-lg text-gray-600 max-w-3xl mx-auto mb-6">
                Navigator Pro. Org is a new nonprofit rooted in the belief that every person deserves a reliable guide through life’s most difficult challenges. Based in Chicago, we provide free, community-based navigation services that connect individuals and families—especially those overlooked or underserved—to essential resources.
            </p>
            <p class="text-xl font-semibold text-lime-600">We are bridge builders. Our mission is to walk alongside people in crisis and help them reclaim stability, dignity, and hope.</p>
        </div>
    </section>

    <!-- Resources Grid Section -->
    <main id="resources" class="flex-grow py-12 px-6">
        <div class="container mx-auto">
            <h2 class="text-4xl font-extrabold text-gray-800 text-center mb-10">Find Essential Resources</h2>

            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 xl:grid-cols-4 gap-8">
                <!-- Resource Cards will be dynamically inserted here by JavaScript -->
            </div>
        </div>
    </main>

    <!-- Footer Section -->
    <footer id="contact" class="bg-gray-900 text-white p-6 mt-auto rounded-t-xl">
        <div class="container mx-auto text-center">
            <h3 class="text-2xl font-bold mb-4">Connect with Navigator Pro. Org</h3>
            <p class="text-lg mb-2">
                We are actively seeking: Seed funding, Collaborators and advisors, Donors and foundation partners.
            </p>
            <p class="text-md mb-4">
                Your time, partnership, and support—at any level—could help Navigator Pro. Org guide hundreds of individuals toward a better future.
            </p>
            <div class="flex flex-col md:flex-row justify-center items-center space-y-2 md:space-y-0 md:space-x-6">
                <p class="text-orange-300"><i class="fas fa-phone-alt mr-2"></i>[Phone Number]</p>
                <p class="text-orange-300"><i class="fas fa-envelope mr-2"></i>[Email Address]</p>
                <p class="text-orange-300"><i class="fas fa-globe mr-2"></i>NavigatorAPP.org</p>
                <!-- Add LinkedIn or other social links if available -->
                <a href="#" class="text-orange-300 hover:text-orange-100 transition-colors"><i class="fab fa-linkedin mr-2"></i>LinkedIn</a>
            </div>
            <p class="mt-6 text-sm text-gray-400">&copy; 2025 Navigator Pro. Org. All rights reserved.</p>
        </div>
    </footer>

    <!-- Resource Detail Modal -->
    <div id="resourceModalBackdrop" class="modal-backdrop"></div>
    <div id="resourceModal" class="modal-content">
        <div class="modal-header">
            <h3 id="modalTitle" class="text-2xl font-bold text-gray-800"></h3>
            <button id="modalCloseBtn" class="modal-close-btn">&times;</button>
        </div>
        <div class="modal-body">
            <p id="modalDescription" class="text-gray-700 mb-4"></p>
            <p class="text-gray-600 text-sm italic">
                For more detailed assistance and direct connections to resources, please contact us directly.
            </p>
            <a href="#contact" id="modalContactBtn" class="bg-lime-500 text-white px-4 py-2 rounded-md hover:bg-lime-600 transition-colors inline-block mt-4">Contact Navigator Pro. Org</a>
        </div>
    </div>

    <script>
        document.addEventListener('DOMContentLoaded', () => {
            const resources = [
                // Basic Needs
                { id: 'food', title: '🍎 Yummy', subtitle: 'Food Assistance', description: 'Food banks, meal programs, and access to groceries to ensure no one goes hungry.', icon: 'fa-utensils' },
                { id: 'housing', title: '🏠 Sweet Home Fix', subtitle: 'Housing & Shelter', description: 'Emergency shelters, housing assistance programs, and support for home repairs to secure safe living.', icon: 'fa-home' },
                { id: 'clothing', title: '👕 Fresh Threads Find', subtitle: 'Clothing & Essentials', description: 'Clothing banks, hygiene products, and essential items for personal well-being.', icon: 'fa-tshirt' },
                { id: 'water', title: '💧 Quench Quest', subtitle: 'Water & Sanitation', description: 'Access to clean water and information on sanitation services for healthy living environments.', icon: 'fa-water' },
                // Health & Well-being
                { id: 'dental', title: '🦷 Smile Sparkle Search', subtitle: 'Dental Care', description: 'Clinics for routine check-ups and emergency dental services.', icon: 'fa-tooth' },
                { id: 'medical', title: '🩺 Body Boost Browse', subtitle: 'Medical Care', description: 'Clinics, urgent care facilities, and specialists for comprehensive health support.', icon: 'fa-stethoscope' },
                { id: 'mental-health', title: '🧠 Mind Mend Menu', subtitle: 'Mental Health Support', description: 'Counseling services, therapy referrals, and support groups for mental well-being.', icon: 'fa-brain' },
                { id: 'wellness', title: '💪 Healthy Habits Hub', subtitle: 'Wellness Resources', description: 'Fitness programs, health education, and resources to promote overall wellness.', icon: 'fa-heartbeat' },
                // Support & Assistance
                { id: 'general-aid', title: '🤝 Helping Hand Hold', subtitle: 'General Assistance', description: 'Information, guidance, and referrals to various support services.', icon: 'fa-hands-helping' },
                { id: 'legal-aid', title: '🗣️ Voice Value Venue', subtitle: 'Legal Aid', description: 'Access to free or low-cost legal services and advice.', icon: 'fa-gavel' },
                { id: 'financial', title: '💰 Budget Buddy Beacon', subtitle: 'Financial Assistance', description: 'Budgeting help, financial aid information, and debt management resources.', icon: 'fa-dollar-sign' },
                { id: 'childcare', title: '👶 Tiny Treasure Tender', subtitle: 'Childcare Support', description: 'Information on daycares, childcare assistance programs, and early learning resources.', icon: 'fa-child' },
                // Learning & Growth
                { id: 'education', title: '📚 Brainy Boost Bazaar', subtitle: 'Education & Training', description: 'Adult education programs, job training, and skill development opportunities.', icon: 'fa-book-open' },
                { id: 'tech-access', title: '💻 Tech Trek Terminal', subtitle: 'Technology Access & Support', description: 'Computer labs, digital literacy training, and access to essential technology.', icon: 'fa-laptop' },
                { id: 'arts-culture', title: '🎨 Creative Canvas Corner', subtitle: 'Arts & Culture', description: 'Free or low-cost cultural programs, art classes, and community creative outlets.', icon: 'fa-palette' },
                // Community & Connection
                { id: 'community-support', title: '🏘️ Neighborly Network Node', subtitle: 'Community Support', description: 'Local groups, volunteer opportunities, and community-building initiatives.', icon: 'fa-users' },
                { id: 'transportation', title: '🚌 Go Getter Gateway', subtitle: 'Transportation Help', description: 'Ride-sharing information, public transit guidance, and transportation assistance.', icon: 'fa-bus' },
                { id: 'animal-welfare', title: '🐾 Furry Friend Finder', subtitle: 'Animal Welfare', description: 'Shelters, pet care resources, and support for animal well-being.', icon: 'fa-paw' },
                // Urgent Needs
                { id: 'emergency', title: '🚨 SOS Signal Spot', subtitle: 'Emergency Assistance', description: 'Crisis lines, immediate help, and rapid response for urgent situations.', icon: 'fa-exclamation-triangle' }
            ];

            const resourcesGrid = document.querySelector('#resources .grid');
            const modal = document.getElementById('resourceModal');
            const modalBackdrop = document.getElementById('resourceModalBackdrop');
            const modalTitle = document.getElementById('modalTitle');
            const modalDescription = document.getElementById('modalDescription');
            const modalCloseBtn = document.getElementById('modalCloseBtn');
            const modalContactBtn = document.getElementById('modalContactBtn');

            // Function to render resource cards
            function renderResourceCards() {
                resourcesGrid.innerHTML = ''; // Clear existing cards
                resources.forEach(resource => {
                    const cardHtml = `
                        <div class="card bg-white p-6 flex flex-col items-center text-center cursor-pointer transform hover:scale-105 transition-transform duration-200" data-id="${resource.id}">
                            <div class="text-5xl text-lime-500 mb-4"> <!-- Icon color changed to lime-500 -->
                                <i class="${resource.icon ? 'fas ' + resource.icon : ''}">${resource.icon ? '' : resource.title.split(' ')[0]}</i>
                            </div>
                            <h3 class="text-xl font-semibold text-gray-800 mb-2">${resource.title}</h3>
                            <p class="text-gray-600 text-sm">${resource.subtitle}</p>
                        </div>
                    `;
                    resourcesGrid.innerHTML += cardHtml;
                });

                // Add event listeners to newly created cards
                document.querySelectorAll('.card').forEach(card => {
                    card.addEventListener('click', () => {
                        const resourceId = card.dataset.id;
                        const selectedResource = resources.find(r => r.id === resourceId);
                        if (selectedResource) {
                            modalTitle.textContent = selectedResource.title + ': ' + selectedResource.subtitle;
                            modalDescription.textContent = selectedResource.description;
                            modal.style.display = 'block';
                            modalBackdrop.style.display = 'block';
                            // Scroll to contact section when 'Contact Navigator Pro. Org' is clicked inside modal
                            modalContactBtn.onclick = () => {
                                modal.style.display = 'none';
                                modalBackdrop.style.display = 'none';
                                document.getElementById('contact').scrollIntoView({ behavior: 'smooth' });
                            };
                        }
                    });
                });
            }

            // Close modal functionality
            function closeModal() {
                modal.style.display = 'none';
                modalBackdrop.style.display = 'none';
            }

            modalCloseBtn.addEventListener('click', closeModal);
            modalBackdrop.addEventListener('click', closeModal); // Close modal when clicking outside

            // Initial render of cards
            renderResourceCards();
        });
    </script>
</body>
</html>
# Navigator
Navigator
