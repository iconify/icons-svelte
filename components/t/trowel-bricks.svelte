<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ynez_acce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="ynez_acce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:trowel-bricks" {...props}></Icon>
