<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j0d4nvb0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="j0d4nvb0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:van-shuttle" {...props}></Icon>
