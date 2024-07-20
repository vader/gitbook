---
description: Accounting Journal Entries
---

# Journal Entries

The [Chart of Accounts](chart-of-accounts.md) is the collection of all your ledger accounts and and within these ledger accounts we add Journal Entries.&#x20;

Journal entries can be manually added or automatically created. They can be a simple transaction or very complex including multiple splits and matches in various currencies.&#x20;

What is common is that every transaction has an opposing transaction.&#x20;

For example if $100 left your Bank Account for travel expenses and you categorized it as Travel & Transportation you will have two transactions even although you only entered one:\
`Bank Account -> Out (Credit)` \
`Travel & Transportation -> $100`&#x20;

{% hint style="info" %}
Business owners:

Most of your accounting transactions will be performed in two places:

\
<mark style="color:green;">Chart of Accounts > Assets > Cash & Cash Equivalents</mark> \ <mark style="color:green;">Chart of Accounts > Liabilities > Credit cards</mark>\
\
In Fiskl you must start your transaction from within these accounts.&#x20;
{% endhint %}

{% hint style="success" %}
Accountants:

Adding journal entries can also be done using the Multi Journal screen.&#x20;
{% endhint %}

#### Simple Journal Entries

A simple journal entry involves two accounts: one debit and one credit. It's the most basic form of a journal entry and is used for straightforward transactions.

**Example:**

* **Transaction:** Purchase of office supplies for cash.
  * **Debit:** Office Supplies
  * **Credit:** Cash

#### Multi Currency Journal Entries

In Fiskl, you can easily create simple journal entries by selecting the relevant accounts and entering the transaction details. The system automatically handles the currency conversion if the transaction involves different currencies, ensuring accurate financial reporting.

{% hint style="info" %}
When you purchase an item in a different currency to your bank account you will find that you have to match different currencies. \
Lets say you have a EUR bank account and travelled to the US and paid $100 for a taxi. \
You have the $100 expense in Fiskl but the amount in your bank shows as -€93

You would choose to match this expense from within Cash & Cash Equivalents \<Your bank ledger account> to the expense. Ensure you have selected all currencies in the match.&#x20;

It may not match so you can use the innovative Auto Adjust FX rate to resolve this.


{% endhint %}
