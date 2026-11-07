<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/x/xwwl7-bgf.css';
import '../../css/s/smlcbcyjn.css';
import '../../css/k/kj2zw7btc.css';
import '../../css/e/er3yhebux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="xwwl7-bgf"/><path class="smlcbcyjn"/><path class="kj2zw7btc"/><path class="er3yhebux"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:widget-add-broken" {...props}></Icon>
