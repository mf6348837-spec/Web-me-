body {
font-family: Tahoma, Arial, sans-serif;
background-color: #f4f6f9;
color: #333;
margin: 0;
padding: 0;
text-align: center;
}

header {
background-color: #1e293b;
color: #ffffff;
padding: 2rem 1rem;
}

header h1 {
margin: 0 0 0.5rem 0;
font-size: 2.2rem;
}

header p {
margin: 0;
color: #94a3b8;
}

.subjects-grid {
display: flex;
flex-wrap: wrap;
justify-content: center;
gap: 20px;
padding: 2rem;
max-width: 1000px;
margin: 0 auto;
}

.card {
background: #ffffff;
border-radius: 8px;
box-shadow: 0 4px 6px rgba(0, 0, 0, 0.08);
padding: 1.5rem;
width: 250px;
text-align: right;
transition: transform 0.2s ease, box-shadow 0.2s ease;
}

.card:hover {
transform: translateY(-4px);
box-shadow: 0 6px 12px rgba(0, 0, 0, 0.12);
}

.card h2 {
color: #0f172a;
margin-top: 0;
border-bottom: 2px solid #3b82f6;
padding-bottom: 0.5rem;
}

.card p {
color: #475569;
font-size: 0.95rem;
line-height: 1.5;
}

.btn {
display: inline-block;
background-color: #2563eb;
color: white;
padding: 0.5rem 1rem;
border-radius: 4px;
text-decoration: none;
margin-top: 1rem;
font-weight: bold;
}

.btn:hover {
background-color: #1d4ed8;
}

footer {
background-color: #e2e8f0;
padding: 1rem;
margin-top: 2rem;
color: #64748b;
font-size: 0.9rem;
}