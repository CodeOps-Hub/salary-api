@Library("my-shared-library") _
// testing  webhook-01
def salaryCI = new org.avengers.template.salary.salaryCI()

node {
    
    def url = 'https://github.com/CodeOps-Hub/Salary-API.git'
    def branch = 'feature/slarayCI'
    def gitLeaksVersion = '8.18.2'
    def reportName = 'credScanReport.json'
    
    salaryCI.call(branch: branch,url: url, gitLeaksVersion, reportName)
    
}
