<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tzlyk9bor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tzlyk9bor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:square-arrow-left" {...props}></Icon>
