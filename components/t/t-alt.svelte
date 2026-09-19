<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ra9pitbyh.css';
import '../../css/d/dwr76qb4e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ra9pitbyh"/><path class="dwr76qb4e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:t-alt" {...props}></Icon>
