<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p3-xn0bej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p3-xn0bej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:tally" {...props}></Icon>
