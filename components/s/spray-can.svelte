<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zp7m-5bvn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="zp7m-5bvn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:spray-can" {...props}></Icon>
