<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/d/dqvkli3td.css';
import '../../css/t/tev0_7rwp.css';
import '../../css/w/wawugdb_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="dqvkli3td"/><path class="tev0_7rwp"/><path class="wawugdb_n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:satellite-broken" {...props}></Icon>
