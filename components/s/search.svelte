<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n3w4gfbgm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":42,"height":42};
const content = `<path class="n3w4gfbgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="topcoat:search" {...props}></Icon>
