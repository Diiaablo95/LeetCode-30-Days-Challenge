# Day 16, 16/04/2020 - Valid Parenthesis String

Given a string containing only three types of characters: '(', ')' and '*', write a function to check whether this string is valid. We define the validity of a string by these rules:

1. Any left parenthesis `'('` must have a corresponding right parenthesis `')'`.
2. Any right parenthesis `')'` must have a corresponding left parenthesis `'('`.
3. Left parenthesis `'('` must go before the corresponding right parenthesis `')'`.
4. `'*'` could be treated as a single right parenthesis `')'` or a single left parenthesis `'('` or an empty string.
5. An empty string is also valid.

**Example 1**:

<code>
Input: "()"

Output: True
</code>

**Example 2**:

<code>
Input: "(*)"

Output: True
</code>

**Example 3**:

<code>
Input: "(*))"

Output: True
</code>

**Note**

1. The string size will be in the range [1, 100].