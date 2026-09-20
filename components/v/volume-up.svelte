<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ap5zc5b2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ap5zc5b2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:volume-up" {...props}></Icon>
