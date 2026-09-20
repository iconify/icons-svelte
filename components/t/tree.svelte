<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vx5nsxb8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="vx5nsxb8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:tree" {...props}></Icon>
