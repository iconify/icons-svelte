<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a3-f0t6_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="a3-f0t6_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:search-plus" {...props}></Icon>
