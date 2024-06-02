const NFTs=[];

function minNFT(model,developer,releasedate,androidversion){
    const NFT={
        "Model" : model,
        "Developer" : developer,
        "Releasedate" : releasedate,
        "AndroidVersion" : androidversion
    }
    NFTs.push(NFT);
}
minNFT("NokiaX","Nokia","2014/02","Android4.1");
minNFT("NokiaC21","HMDGlobal","2022/05","Android11");
minNFT("OppoReno3","Oppo","2020/03","Android10");
minNFT("SamsungGalaxyS21Ultra","SamsungElectronics","2021/01","Android 11");


function listNFTs(){
    for(let i=0;i<NFTs.length ;i++){
        console.log("\nPhone:"+(i+1));
        console.log("Model:" +NFTs[i].Model);
        console.log("Developer:" +NFTs[i].Developer);
        console.log("Releasedate:" +NFTs[i].Releasedate);
        console.log("AndroidVersion:"+ NFTs[i].AndroidVersion);
    }
}
listNFTs();


function getTotalSupply(){
    console.log("\n"+NFTs.length);
}
getTotalSupply();
