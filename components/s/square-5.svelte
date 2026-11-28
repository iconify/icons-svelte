<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2u52mb5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k2u52mb5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:square-5" {...props}></Icon>
