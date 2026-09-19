<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ls6_xn_4i.css';
import '../../css/m/m26d08bnp.css';
import '../../css/s/sxmz7tbxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="ls6_xn_4i"><path class="m26d08bnp"/><path class="sxmz7tbxf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:text" {...props}></Icon>
