# Created by Paul Nagy
# Copyright by Paul Nagy 2015
# This program is intended to store stock tickers and display info about the stocks.

import csv
import os
import sys


# menu 1
# 1 new portfolio
# 2 load portfolio
def introduction_menu():
    choice = 0
    print("***********************************************************************************")
    print("*                                                                                 *")
    print("*                                 What do you want to do yo?                      *")
    print("*                                                                                 *")
    print("*                                   (O)pen Portfolio                              *")
    print("*                                   (N)ew Portfolio                               *")
    print("*                                   (Q)uit                                        *")
    print("*                                                                                 *")
    print("***********************************************************************************")
    choice = str(input())
    if choice.upper() == 'O':
        # open portfolio
        for file_name in os.listdir("."):
            print("open_test")  # to test if statement
    elif choice.upper() == 'N':
        # new portfolio
        file_name = input("What would you like to Name the File?")
        file_name = file_name + ".csv"
        new_file = open(file_name, "a")
        application_menu()
    elif choice.upper() == 'Q':
        # for quitting program
        print("figure out how to quit program")
    elif choice.upper() != 'O' or 'N':
        print("NO!!!!!!!!!!!!!!!!!!!!!!!!!!!!")
        introduction_menu()


# menu 2
# 1 add stock
# 2 sell stock
# 3 display Portfolio
# 4 report
def application_menu():
    print("\n")
    print("Make A Selection:")
    print("(D)isplay Portfolio")
    print("(A)dd A New Stock")
    print("(S)ell A Stock")
    option = str(input())
    if option.upper() == 'D':
        print("D")
    elif option.upper() == 'A':
        print("A")
    elif option.upper() == 'R':
        print("R")
    elif option.upper() != 'D' or 'A' or 'R':
        print("nope")




# for adding a stock to the portfolio
def add_stock(stock_portfolio):
    ticker=input("Enter a ticker symbol to add")
    qty=int(input("How many did you buy?"))


# for deleting a stock from the portfolio
def sell_stock(stock_portfolio):
    sell_ticker=input("Enter a ticker symbol to remove")



def retrieve_data():
    pass

def display_portfolio(stock_portfolio):
    # to display portfolio
    pass


def main():
    # runs program
    introduction_menu()

def portfolio():
    # to hold portfolio
    ticker_index=[]
    qty_index=[]
    company_index=[]
    price_index=[]
    value_index=[]
    stock_portfolio=[ticker_index,company_index,qty_index,price_index,value_index]
    total_portfolio_value=sum(value_index)
    return stock_portfolio

def table_look():  # screen template
    print("Current total portfolio value is: $ ")
    print("|    Ticker    |         Company         |    QTY   |     Price    |       Value     |")
    portfolio()

main()


# phoneList = [['Billy Bob Jones', '651-405-2345'], list of list for string complex info
#          ['Xavier Brown', '763-506-6789'],
#       ['Sue Smith', '612-789-0011']]
# https://greenido.wordpress.com/2009/12/22/yahoo-finance-hidden-api/
# openbookproject.net/pybiblio/practice/wilson/portfolio.php
# http://sagenb.org/src/finance/stock.py
