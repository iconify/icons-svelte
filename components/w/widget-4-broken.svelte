<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/p/p_8xklbbj.css';
import '../../css/g/g8fm3s2qb.css';
import '../../css/r/r7eg7804v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="p_8xklbbj"/><path class="g8fm3s2qb"/><path class="r7eg7804v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:widget-4-broken" {...props}></Icon>
