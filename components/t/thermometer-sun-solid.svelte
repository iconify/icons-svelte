<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/i/idnkkabej.css';
import '../../css/l/l4eea2gkm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="n1lsf0bnc"><path class="idnkkabej"/><path class="l4eea2gkm wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:thermometer-sun-solid" {...props}></Icon>
