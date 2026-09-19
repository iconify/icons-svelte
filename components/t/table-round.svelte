<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/g/g5d36ybqm.css';
import '../../css/n/nm32_xbfm.css';
import '../../css/f/fcgvesbjd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><ellipse class="g5d36ybqm"/><path class="nm32_xbfm"/><path class="fcgvesbjd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:table-round" {...props}></Icon>
