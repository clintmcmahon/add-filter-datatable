<!doctype html>

<html lang="en">

<head>
  <meta charset="utf-8">

  <title>Add select drop-down filter to DataTable</title>
  <meta name="description" content="">
  <link rel="stylesheet" href="https://cdn.datatables.net/1.10.23/css/jquery.dataTables.min.css" />
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" />
<style>
  select.form-control{
    display: inline;
    width: 200px;
    margin-left: 25px;
  }
</style>
</head>

<body>
  <div class="container mt-4">
    <!-- Create the drop down filter -->
    <div class="category-filter">
      <select id="categoryFilter" class="form-control">
        <option value="">Show All</option>
        <option value="Classical">Classical</option>
        <option value="Hip Hop">Hip Hop</option>
        <option value="Jazz">Jazz</option>
      </select>
    </div>

    <!-- Set up the datatable -->
    <table class="table" id="filterTable">
      <thead>
        <tr>
          <th scope="col">Artist</th>
          <th scope="col">Category</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td scope="col">Public Enemy</td>
          <td scope="col">Hip Hop</td>
        </tr>
        <tr>
          <td scope="col">Chet Baker</td>
          <td scope="col">Jazz</td>
        </tr>
        <tr>
          <td scope="col">Billie Holiday</td>
          <td scope="col">Jazz</td>
        </tr>
        <tr>
          <td scope="col">Vivaldi</td>
          <td scope="col">Classical</td>
        </tr>
        <tr>
          <td scope="col">Jurrasic 5</td>
          <td scope="col">Hip Hop</td>
        </tr>
        <tr>
          <td scope="col">Onyx</td>
          <td scope="col">Hip Hop</td>
        </tr>
        <tr>
          <td scope="col">Tchaikovsky</td>
          <td scope="col">Classical</td>
        </tr>
        <tr>
          <td scope="col">Oscar Peterson</td>
          <td scope="col">Jazz</td>
        </tr>
      </tbody>
    </table>

  </div>

  <script src="https://code.jquery.com/jquery-3.5.1.min.js"
    integrity="sha256-9/aliU8dGd2tb6OSsuzixeV4y/faTqgFtohetphbbj0=" crossorigin="anonymous"></script>

  <script src="https://cdn.datatables.net/1.10.23/js/jquery.dataTables.min.js"></script>

  <script>
    $("document").ready(function () {

      $("#filterTable").dataTable({
        "searching": true
      });

      //Get a reference to the new datatable
      var table = $('#filterTable').DataTable();

      //Take the category filter drop down and append it to the datatables_filter div. 
      //You can use this same idea to move the filter anywhere withing the datatable that you want.
      $("#filterTable_filter.dataTables_filter").append($("#categoryFilter"));
      
      //Get the column index for the Category column to be used in the method below ($.fn.dataTable.ext.search.push)
      //This tells datatables what column to filter on when a user selects a value from the dropdown.
      //It's important that the text used here (Category) is the same for used in the header of the column to filter
      var categoryIndex = 0;
      $("#filterTable th").each(function (i) {
        if ($($(this)).html() == "Category") {
          categoryIndex = i; return false;
        }
      });

      //Use the built in datatables API to filter the existing rows by the Category column
      $.fn.dataTable.ext.search.push(
        function (settings, data, dataIndex) {
          var selectedItem = $('#categoryFilter').val()
          var category = data[categoryIndex];
          if (selectedItem === "" || category.includes(selectedItem)) {
            return true;
          }
          return false;
        }
      );

      //Set the change event for the Category Filter dropdown to redraw the datatable each time
      //a user selects a new filter.
      $("#categoryFilter").change(function (e) {
        table.draw();
      });

      table.draw();
    });
  </script>
</body>

</html>