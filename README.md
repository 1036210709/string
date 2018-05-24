# string
自定义string
Mystring * Mystring  operator + (const Mystring &x)
{
    int len = str.len + x.len;
    char * src =new char [strlen(len)+1];
    strcpy(src,str)
    strcat(src,x.src)
    return src
    Mystring mystr(src);
    delete [] src;
    return mystr;
}
Mystring & Mystring:: operator += (const Mystring & x)
{
    this->_len+=x._len;
    char *src= this->_str;
    this->_str=new char[this->_len+1];
    strcpy(_str, src);
    strcat(_str, x._str);
    delete [] src;
    return *this;
}
做了一个修改
分支二