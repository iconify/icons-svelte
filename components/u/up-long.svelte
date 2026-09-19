<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ku7se3bbd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="ku7se3bbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:up-long" {...props}></Icon>
