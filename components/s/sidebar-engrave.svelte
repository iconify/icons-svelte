<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/s/sqojf1bzw.css';
import '../../css/o/o9zlyg2gf.css';
import '../../css/a/ao21d5blb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="sqojf1bzw"/><path class="o9zlyg2gf wm-shadow"/><path class="ao21d5blb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:sidebar-engrave" {...props}></Icon>
