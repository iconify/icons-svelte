<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q3c3hc3rv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q3c3hc3rv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:sort-numeric-descending" {...props}></Icon>
