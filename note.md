DataTable: testResults

ArrayRow: {CurrentRow("Order"), CurrentRow("Action").ToString(), CurrentRow("Expected").ToString(), "Failed", ex.Message, Now.ToString("yyyy-MM-dd HH:mm:ss")}