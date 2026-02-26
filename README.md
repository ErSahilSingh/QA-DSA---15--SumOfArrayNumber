# QA-DSA---15--SumOfArrayNumber
function sumArray(arr) {
  if (!Array.isArray(arr)) {
    return 0
  }
  let totalcount = 0
  for (let i = 0; i < arr.length; i++) {
    totalcount = totalcount + arr[i]
  }
  return totalcount
}

module.exports = { sumArray };
