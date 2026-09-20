<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u4-l-qb9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="u4-l-qb9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:truck-loading-solid" {...props}></Icon>
