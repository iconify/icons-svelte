<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/u/u0c9hej4a.css';
import '../../css/p/pbd07ubhl.css';
import '../../css/h/hyww7bdrb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="u0c9hej4a"/><path class="pbd07ubhl"/><path class="hyww7bdrb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:submerge" {...props}></Icon>
