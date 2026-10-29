<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/s/suzw7xbbl.css';
import '../../css/k/kivd_7bqx.css';
import '../../css/v/vhm99pbwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="suzw7xbbl wm-k"/><path class="kivd_7bqx wm-k"/><path class="vhm99pbwe wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:snowflake-sketch" {...props}></Icon>
