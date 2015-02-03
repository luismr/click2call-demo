click2call-demo
===============

How to implement LigFlat Click2Call examples

It uses cross site scripting to host all Click2Call Javascript, CSS, WAV and another assets.


##General Example

    <!-- Button to Make the Call -->
    <button class="click2call-btn">
        <i class="icon-phone"></i>
        Ligue Já</button>

    <script type="text/javascript" src="http://api.ligflat.com.br/click2call/lib/jquery.min.js"></script>
    <script type="text/javascript" src="http://api.ligflat.com.br/click2call/click2call.min.js"></script>

    <script type="text/javascript">
    jQuery(function($)
    {
        /*
         * Put your LigFlat ID below
         */
        $('.click2call-btn').click2call({
            id: 'you-ligflat-id',
        });
    });
    </script>
