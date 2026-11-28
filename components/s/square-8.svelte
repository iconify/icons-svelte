<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eyf-vcdxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eyf-vcdxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:square-8" {...props}></Icon>
