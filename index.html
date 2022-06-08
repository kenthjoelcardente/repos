
<HTML>

<HEAD>
    <TITLE>PHP RSS Feed Read and List</TITLE>
    <style>
        body {
            width: 610;
        }

        .rss-table {
            width: 100%;
            border-spacing: initial;
            margin: 20px 0px;
            word-break: break-word;
            table-layout: auto;
            line-height: 1.8em;
            color: #333;
        }

        .rss-table th {
            background: #999 url('feed.png') no-repeat 10px;
            padding: 8px 30px 5px;
            text-align: left;
            color: #FFF;
        }

        .rss-table td {
            border-bottom: #f0f0f0 1px solid;
            background-color: #ffffff;
            padding: 5px;
        }

        .rss-table td a.feed_title {
            text-decoration: none;
            color: #00d4ff;
            font-weight: bold;
        }
    </style>
</HEAD>

<BODY>
    <?php
    $rss_feed = simplexml_load_file("http://rss.cnn.com/rss/edition_space.rss");
    ?>
    <table class="rss-table">
        <tbody>
            <tr>
                <th><strong>PhpPot RSS Feed</strong></th>
            </tr>
            <?php
            if (!empty($rss_feed)) {
                $i = 0;
                foreach ($rss_feed->channel->item as $feed_item) {
                    if ($i >= 10) break;
            ?>
                    <tr>
                        <td valign="top">
                            <div><a class="feed_title" href="<?php echo $feed_item->link; ?>"><?php echo $feed_item->title; ?></a></div>
                            <div><?php echo implode(' ', array_slice(explode(' ', $feed_item->description), 0, 14)) . "..."; ?></div>
                        </td>
                    </tr>
            <?php
                    $i++;
                }
            }
            ?>
        </tbody>
    </table>
</BODY>

</HTML>