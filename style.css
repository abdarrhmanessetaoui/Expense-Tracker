* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  background: linear-gradient(135deg, #2e8b57, #a8d5ba);
  min-height: 100vh;
  font-family: "Poppins", sans-serif;
  display: flex;
  align-items: center;
  justify-content: center;
  padding: 20px;
  color: #2d3436;
}

.container {
  width: 100%;
  max-width: 1200px;
  background-color: #fff;
  padding: 2rem;
  border-radius: 24px;
  box-shadow: 0 12px 24px rgba(0, 0, 0, 0.15);
}

h1 {
  text-align: center;
  color: #1a202c;
  margin-bottom: 35px;
  font-size: 2.2rem;
  font-weight: 600;
  letter-spacing: -0.5px;
}

h2 {
  color: #2d3748;
  margin-bottom: 1rem;
  font-size: 1.25rem;
  font-weight: 500;
}

.balance-container {
  text-align: center;
  margin-bottom: 35px;
  padding: 24px;
  background: linear-gradient(135deg, #a8d5ba, #6b8e23);
  border-radius: 1rem;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.05);
}

.balance-container h1 {
  font-size: 3rem;
  margin: 15px 0;
}

.summary {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 24px;
  margin-top: 24px;
}

.main-content {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 24px;
}

.income,
.expenses {
  background-color: white;
  padding: 24px;
  border-radius: 1rem;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.05);
  transition: transform 0.2s ease;
}

.income:hover,
.expenses:hover {
  transform: translateY(-2px);
}

.income h3 {
  color: #059669;
  font-size: 1.1rem;
  font-weight: 500;
}

.expenses h3 {
  color: #dc2626;
  font-size: 1.1rem;
  font-weight: 500;
}

.income p,
.expenses p {
  margin-top: 8px;
  font-size: 1.75rem;
  font-weight: 600;
}

.income p {
  color: #059669;
}

.expenses p {
  color: #dc2626;
}

.transaction-container {
  height: 100%;
  display: flex;
  flex-direction: column;
}

#transaction-list {
  list-style: none;
  max-height: 500px;
  overflow-y: auto;
  padding-right: 8px;
  flex-grow: 1;
}

#transaction-list::-webkit-scrollbar {
  width: 8px;
}

#transaction-list::-webkit-scrollbar-track {
  /* track is the bg of the scrollbar */
  background-color: #f1f1f1;
  border-radius: 4px;
}
#transaction-list::-webkit-scrollbar-thumb {
  /* thumb is the draggble part of the scrollbar */
  background-color: #cbd5e0;
  border-radius: 4px;
}
#transaction-list::-webkit-scrollbar-thumb:hover {
  background-color: #a0aec0;
}

.transaction {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 1rem 1.2rem;
  margin-bottom: 12px;
  border-radius: 12px;
  background-color: #fff;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.05);
  transition: all 0.2s ease;
  border-right: 5px solid;
  animation: slideIn 0.3s ease;
}

@keyframes slideIn {
  from {
    opacity: 0;
    transform: translateX(-20px);
  }

  to {
    opacity: 1;
    transform: translateX(0px);
  }
}

.transaction:hover {
  transform: translateX(4px);
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
}

.transaction.income {
  border-right-color: #059669;
}

.transaction.expense {
  border-right-color: #dc2626;
}

.transaction .delete-btn {
  background: none;
  border: none;
  color: #dc2626;
  cursor: pointer;
  font-size: 1.4rem;
  opacity: 0;
  transition: all 0.2s ease;
  padding: 4px 8px;
  border-radius: 4px;
  margin-left: 12px;
}

.transaction:hover .delete-btn {
  opacity: 1;
}

.transaction .delete-btn:hover {
  background-color: #fee2e2;
  transform: scale(1.1);
}

.form-container {
  background: linear-gradient(135deg, #f6f8fb, #f1f4f8);
  padding: 24px;
  border-radius: 16px;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.15);
  height: 100%;
  display: flex;
  flex-direction: column;
}

.form-container form {
  height: 100%;
  display: flex;
  flex-direction: column;
}

.form-group {
  margin-bottom: 20px;
}

label {
  display: block;
  margin-bottom: 8px;
  color: #4a5568;
  font-weight: 500;
}

input {
  width: 100%;
  padding: 12px 16px;
  border: 2px solid #e2e8f0;
  border-radius: 8px;
  font-size: 1rem;
  transition: all 0.2s ease;
  background-color: white;
}

input:focus {
  outline: none;
  border-color: #667eea;
  box-shadow: 0 0 0 3px rgba(102, 126, 234, 0.1);
}

input:hover {
  border-color: #cbd5e0;
}

small {
  color: #718096;
  font-size: 0.875rem;
  margin-top: 4px;
  display: block;
}

button[type="submit"] {
  width: 100%;
  padding: 14px;
  background: linear-gradient(135deg, #2e8b57 0%, #3cb371 100%);
  color: white;
  border: none;
  border-radius: 8px;
  cursor: pointer;
  font-size: 1rem;
  font-weight: 500;
  transition: all 0.2s ease;
  box-shadow: 0 4px 12px rgba(102, 126, 234, 0.2);
  margin-top: auto;
}

button[type="submit"]:hover {
  transform: translateY(-2px);
  box-shadow: 0 6px 16px rgba(102, 126, 234, 0.3);
}

button[type="submit"]:active {
  transform: translateY(0);
}

/* responsiveness */

@media (max-width: 900px) {
  .main-content {
    grid-template-columns: 1fr;
  }

  #transaction-list {
    max-height: 300px;
  }
}

@media (max-width: 480px) {
  .container {
    padding: 24px;
  }

  .summary {
    grid-template-columns: 1fr;
    gap: 16px;
  }

  .balance-container h1 {
    font-size: 2.5rem;
  }

  .income p,
  .expenses p {
    font-size: 1.5rem;
  }

  .transaction {
    padding: 14px 16px;
  }

  h1 {
    font-size: 1.8rem;
  }
}
