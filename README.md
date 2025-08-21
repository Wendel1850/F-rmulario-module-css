# F-rmulario-module-css
/* Formulario.module.css */
.container {
  max-width: 500px;
  margin: 40px auto;
  padding: 20px;
  background-color: #f9f9f9;
  border: 1px solid #ddd;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

.title {
  font-size: 24px;
  font-weight: bold;
  margin-bottom: 20px;
}

.form {
  display: flex;
  flex-direction: column;
}

.field {
  margin-bottom: 20px;
}

.label {
  font-size: 16px;
  font-weight: bold;
  margin-bottom: 10px;
}

.input, .textarea {
  width: 100%;
  padding: 10px;
  font-size: 16px;
  border: 1px solid #ccc;
}

.input:focus, .textarea:focus {
  border-color: #aaa;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

.error {
  color: #f00;
  font-size: 14px;
  margin-top: 5px;
}

.button {
  background-color: #4CAF50;
  color: #fff;
  padding: 10px 20px;
  border: none;
  border-radius: 5px;
  cursor: pointer;
}

.button:hover {
  background-color: #3e8e41;
}
