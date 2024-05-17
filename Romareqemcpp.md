#include <iostream>

using namespace std;
int main() {
    char roma[]={'M','D','C','L','X','V','I'};
    int a,b;
    string input;
    
    cout<<"Enter:";
    cin>>input;
    
    //En boyuk roma reqemi mueyyenlesdirme
    int bigRomaIndex;
    for(int i=0;i<7;i++){
        for(int l=0;l<input.length();l++){
        	if(input[l]==roma[i]){
        		bigRomaIndex=l;
        		break;
			}
			else{
				bigRomaIndex=-1;
			}
			
		}
    }
    cout<<bigRomaIndex;
    
    //Netice
    
    return 0;
}
