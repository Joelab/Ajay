# Ajay
Testing
public boolean aIsBigger(int a, int b) {
  if (a > b && (a - b) >= 2) {
    return true;
  }

  return false;
}

Alternately it can be done with an if/else structure like this:

public boolean aIsBigger(int a, int b) {
  if (a > b && (a - b) >= 2) {
    return true;
  } else {
    return false;
  }
}

And in fact, since the boolean test is true when we want to return true, and false when we want to return false, it can be written as a one-liner like this:

public boolean aIsBigger(int a, int b) {
  return (a > b && (a - b) >= 2);
}
// This works
public boolean foo() {
  if (something) {
    return true;
  }

  return false;
}

Or fill out the if/else structure so that every path has a return:

// This works
public boolean foo() {
  if (something) {
    return true;
  }
  else {
    return false;
  }
}

