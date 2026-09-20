<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ntg1e198n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="ntg1e198n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:wrench" {...props}></Icon>
