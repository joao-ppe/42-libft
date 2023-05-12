# **42 / COMMON CORE / LIBFT**  
My first library in C language. Project for 42 Porto.  
  
### **String & Character Manipulation Functions:**  
`ft_isalpha` - Verifies if a character is **alphabetic**.  
`ft_isdigit` - Verifies if a character is a **_digit_**.  
`ft_isalnum` - Verifies if a character is **alphabetic and numeric**.  
`ft_isascii` - Verifies if a character is **part of the ascii table**.  
`ft_isprint` - Verifies if a character is **printable**.  
`ft_toupper` - Converts an alphabetic character to **uppercase**.  
`ft_tolower` - Converts an alphabetic character to **lowercase**.  
`ft_strlen` - Returns the **length of a string**.  
`ft_strchr` - Returns a pointer to the **first occurrence** of a **character** in a string.  
`ft_strrchr` - Returns a pointer to the **first occurrence** of a **character** in a string, starting from the end of the string.  
`ft_strncmp` - Compares two strings: string 1 and string 2 and returns an integer as result.  
`ft_strlcpy` - Copies a string (src) to another string (dst).  
`ft_strlcat` - Concatenates two strings: src and dst.  
`ft_strnstr` - Finds the **first occurrence** of a **substring** in a **string** and returns a pointer to the beggining of the located substring.  
`ft_strdup` -  Returns a pointer to a **new string** which is a duplicate of the string **src**.  
`ft_atoi` - Converts a **string of digits** to an **integer** value. (Ascii To Integer)  
`ft_substr` - **Allocates memory** and returns a **substring** from the string ’s’.  
`ft_strjoin` - **Allocates memory** and returns a **new string**, which is the **concatenation of ’s1’ and ’s2’**.  
`ft_strtrim` - **Allocates memory** and returns a **copy of a string** with the characters specified in **’set’** removed from the **beginning and the end** of the string.  
`ft_split` - **Allocates memory** and returns an **array of strings** obtained by **splitting the original string** using the character **’c’** as a delimiter.  
`ft_itoa` - **Allocates memory** and returns a **string/array** representing the **integer received** as an argument.  
`ft_strmapi` - Applies the **function ’f’** to **each character of a string**. Returns a **new allocated string** with the successive aplications of **’f’**.  
`ft_striteri` - Applies the **function ’f’** on **each character of the string** passed as argument, passing its index as first argument.  
`ft_putchar_fd` - Outputs the **character ’c’** to the given **file descriptor**.  
`ft_putstr_fd` - Outputs the **string ’s’** to the given **file descriptor**.  
`ft_putendl_fd` - Outputs the **string ’s’** to the given **file descriptor**, followed by a **newline**.  
`ft_putnbr_fd` - Outputs the **integer ’n’** to the given **file descriptor**.  


### **Memory Manipulation Functions:**  
`ft_memset` - Fills the first **n** bytes of an **array** with a **determined character**.  
`ft_bzero` - Fills the first **n** bytes of an **array** with the **null character**.  
`ft_memcpy` - Copies n bytes from **src to dest**. The memory areas must **not overlap**.  
`ft_memmove` - Copies **n** bytes from **src** to **dest**. The memory areas **may overlap**.  
`ft_memchr` - Scans the initial **n** bytes of a **string** for the **first instance of a character**.  
`ft_memcmp` - Compares the first **n** bytes of **string 1** and **string 2**.  
`ft_calloc` -  **Allocates  memory for an array** of **nmemb elements** of **size bytes** each and returns a **pointer** to the **allocated memory**.  

### **Linked Lists Functions:**  
`ft_lstnew` - **Allocates memory** and returns a **new node**.  
`ft_lstadd_front` - Adds the **node ’new’** at the **beginning** of the list.  
`ft_lstsize` - Counts the **number of nodes** in a list.  
`ft_lstlast` - Returns the **last node** of the list.  
`ft_lstadd_back` - Adds the **node ’new’** at the **end** of the list.  
`ft_lstdelone` - **Frees the memory** of the given **node’s content** using the **function ’del’**, and **frees the node**.  
`ft_lstclear` - **Deletes and frees** the given node and every **successor**.  
`ft_lstiter` - Iterates a list and applies the **function ’f’** on the **content of each node**.  
`ft_lstmap` - Iterates a list and applies the **function ’f’** on the content of each node. **Returns a new list** after the successive applications of the **function ’f’**.  

# Grade: **125%**.
