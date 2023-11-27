.calculator {
    max-width: 300px;
    margin: 0 auto;
    background-color: black;
    border: 2px solid #ccc;
    border-radius: 10px;
}

.calculator .display {
    width: 100%;
    height: 60px;
    font-size: 24px;
    text-align: right;
    padding: 5px 10px;
    border: none;
    outline: none;
}

.calculator .buttons {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    grid-gap: 5px;
    margin: 10px;
}

.calculator .button {
    width: 100%;
    height: 50px;
    font-size:  20px;
    background-color: #808a8d;
    color: #fff;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

.calculator .button:hover {
    background-color: #555;
}

.calculator .button.clear {
    background-color: #f00;
}

.calculator .button.clear:hover {
    background-color: #d00;
}
