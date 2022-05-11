# Pychain_Ledger

This blockchain ledger allows banks to make financial transactions and record the data in the blockchain. This ledger uses Streamlit to create a user friendly web interface so that they can select the sender, receiver, and transaction amount. After the selections are made, the user can add the block and and validate the chain. 

---

## Approach

1. Create a data class, "Record", that includes the sender, receiver, and transaction amount.
2. Create a data class named "Block" to create and hash the blocks.
3. Create a data class named "Pychain" that links together and creates methods for proof of work and validating the blockchain. 
4. Create the Streamlit interface.
5. Add user inputs via Streamlit and test the Pychain Ledger.

---

## Technologies

This project uses the standard Python 3.8 and requires the following libraries and/or dependencies:

- [Pandas](https://pandas.pydata.org/) - a software library designed for open source data analysis and manipulation.
- [datetime](https://docs.python.org/3/library/datetime.html) - supplies classes for manipulating date and time. 
- [Streamlit](https://streamlit.io/) - turns datascripts into a shareable web apps. 
- [dataclasses](https://docs.python.org/3/library/dataclasses.html) - a decorator that is used to add generated special methods to classes.
- [typing](https://docs.python.org/3/library/typing.html) - provides runtime support for type hints. 
- [hashlib](https://docs.python.org/3/library/hashlib.html) - implements a common interface to many different secure hash and message digest algorithms. 

---

## Results via Streamlit

![](https://github.com/ThomasBrierton/Pychain_Ledger/blob/main/Photos/Screen%20Shot%202022-05-05%20at%2011.16.47%20AM.png)

![](https://github.com/ThomasBrierton/Pychain_Ledger/blob/main/Photos/Screen%20Shot%202022-05-05%20at%2011.17.32%20AM.png)

![](https://github.com/ThomasBrierton/Pychain_Ledger/blob/main/Photos/Screen%20Shot%202022-05-05%20at%2011.18.52%20AM.png)

![](https://github.com/ThomasBrierton/Pychain_Ledger/blob/main/Photos/Streamlit_gif.gif)

---

## Contributors 

Thomas Brierton and UCB

---

## License

MIT

