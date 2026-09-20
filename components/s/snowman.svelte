<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yb74phbvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="yb74phbvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:snowman" {...props}></Icon>
