<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/d/dncd5rb1n.css';
import '../../css/i/iue80nb2y.css';
import '../../css/f/fky6n3bak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="dncd5rb1n"/><path class="iue80nb2y"/><path class="fky6n3bak"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:truck-length" {...props}></Icon>
