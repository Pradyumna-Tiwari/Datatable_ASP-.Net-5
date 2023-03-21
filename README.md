# Datatable_ASP-.Net-5
#lets write the code and procedure, how to add datatable
#first of all, we would add some libraries in head of  _layout.cshtm.

<!-- CSS library -->
    <link rel="stylesheet" type="text/css" href="https://cdn.datatables.net/v/dt/dt-1.13.2/datatables.min.css" />

    <script type="text/javascript" src="https://cdn.datatables.net/v/dt/dt-1.13.2/datatables.min.js"></script>
    <!-- jQuery library -->
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.6.1/jquery.min.js"></script>

    <!-- Datatable library -->
    <script src="https://cdn.datatables.net/1.13.1/js/jquery.dataTables.min.js"></script>

    <!-- Latest compiled JavaScript -->
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>
    
    <!--simply add these files in body of _layout.cshtml and then--!>
    
     @Styles.Render("~/Content/css")
    @Scripts.Render("~/bundles/modernizr")
    
    <!--and then add jquery function in which page where you want to implement data table --!>
    
<script>
    $(document).ready(function () {
        $('#aaa').DataTable();
        
    });
</script>


  <!-- aaa is the datatable id --!>

<!--you should add <thead> for headings of data table and for data you should use <tbody>. in <tbody> your all the table will be show.--!>

  <!-- in the <table></table>, you have to mention your id like this --!>

  <!-- your full page shuld be like this --!>
<table id="aaa">
<thead></thead>
<tbody></tbody>
</table>
<script>
    $(document).ready(function () {
        $('#aaa').DataTable();
        
    });
</script>


  <!-- if you still have any query DM me on instagram --!>

    
