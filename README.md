# THE STYLING
.form-container {
    background-color: var(--card-bg);
    border-radius: var(--border-radius);
    box-shadow: 0px 10px 30px rgba(0, 0, 0, 0.3);
    width: 100%;
    max-width: 800px;
    border-radius: 12px;
    padding: 2.5rem;
    animation: fadeIn 0.5s ease-out;
    overflow: hidden;
}


@keyframes fadeIn {
    from {
        opacity: 0;
        transform: translateY(20px);
    }

    to {
        opacity: 1;
        transform: translateY(0px);
    }
}

# THE HTML
