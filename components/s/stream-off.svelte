<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ub4cgse3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ub4cgse3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:stream-off" {...props}></Icon>
