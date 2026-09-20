<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zv6kmxbpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="zv6kmxbpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:shuffle" {...props}></Icon>
