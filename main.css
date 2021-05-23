

var count = 0;
var thiscount = 0;

const handler = {
    startInitFunctionOrder(order) {
        count = data.count
        },
    initfunctioninvoking(data){
        document.querySelector(".progressbar").style.left = "0%"
        document.querySelector(".progressbar").style.width = ((data.idx / count) * 100) + "%"
    },
    startdatafileentries(data) {
        count = data.count;
    },
    performmaploadfunction(data) {
        ++thiscount
        document.querySelector(".progressbar").style.left = "0%"
        document.querySelector(".progressbar").style.width = ((thiscount / count) * 100) + "%"
    }
}

window.addEventListener("message", function(e){
    (handler[e.data.evenname] || function () {})(e.data)
})
