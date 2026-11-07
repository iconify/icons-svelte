<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/f/fh6a-dbrt.css';
import '../../css/p/p2-mbsbue.css';
import '../../css/w/w8w5t9ikw.css';
import '../../css/y/y1yk9n5ra.css';
import '../../css/k/k218w6buj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="fh6a-dbrt"/><path class="p2-mbsbue"/><path class="w8w5t9ikw"/><path class="y1yk9n5ra"/><path class="k218w6buj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:trash-bin-trash-broken" {...props}></Icon>
