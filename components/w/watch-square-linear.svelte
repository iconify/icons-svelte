<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/g/g9v60on3f.css';
import '../../css/e/e1_dsdb2x.css';
import '../../css/f/fdsu-dbih.css';
import '../../css/e/e8n1d8bgz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="g9v60on3f"/><path class="e1_dsdb2x"/><path class="fdsu-dbih"/><path class="e8n1d8bgz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:watch-square-linear" {...props}></Icon>
