const getLiveness = async () => {
    web3Provider.eth.net.isListening()
        .then(() => console.log(`-> web3 provider is connected`))
        .catch(e => console.log('error: ' + e));
}
