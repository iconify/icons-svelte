<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/y/y9lk8-blp.css';
import '../../css/k/krpz13i1y.css';
import '../../css/u/uvaq53bno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="y9lk8-blp"/><path class="krpz13i1y"/><path class="uvaq53bno"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:shared-wifi" {...props}></Icon>
