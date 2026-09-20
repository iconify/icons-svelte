<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ti0vu-b3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ti0vu-b3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:station" {...props}></Icon>
