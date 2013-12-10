Pax-Ludens
==========

Alternative Story
<script type="text/javascript">
  window.onload = function() { init() };

  var public_spreadsheet_url = 'https://docs.google.com/a/pio.carrollu.edu/spreadsheet/pub?key=0AkjDiRGV5660dFpaLXhnUzlxZlZhYnRrYW1nbVp2Smc&single=true&gid=0&output=html';

  function init() {
    Tabletop.init( { key: public_spreadsheet_url,
                     callback: showInfo,
                     simpleSheet: true } )
  }

  function showInfo(data, tabletop) {
    alert("Successfully processed!")
    console.log(data);
  }
</script>
