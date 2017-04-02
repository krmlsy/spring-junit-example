# Örnek Assertion Kullanımları
## 1- Checks that two primitives/objects are equal.
void assertEquals(boolean expected, boolean actual)

## 2- Checks that a condition is true.
void assertTrue(boolean expected, boolean actual)

## 3- Checks that a condition is false.	
void assertFalse(boolean condition)

## 4- Checks that an object isn't null.
void assertNotNull(Object object)

## 5- Checks that an object is null.
void assertNull(Object object)

## 6- The assertSame() method tests if two object references point to the same object.
void assertSame(boolean condition)

## 7- The assertNotSame() method tests if two object references do not point to the same object.
void assertNotSame(boolean condition)

## 8- The assertArrayEquals() method will test whether two arrays are equal to each other.
void assertArrayEquals(expectedArray, resultArray);
