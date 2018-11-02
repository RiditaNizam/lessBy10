public boolean lessBy10(int a, int b, int c) {
  
  if(a - b >= 10){
    return true;
  }
  
  else if(b - a >= 10){
    return true;
  }
  
  else if(a - c >= 10){
    return true;
  }
  
  else if(c - a >= 10){
    return true;
  }
  
  else if(b - c >= 10){
    return true;
  }
  
  else if(c - b >= 10){
    return true;
  }
  
  return false;
  
}
