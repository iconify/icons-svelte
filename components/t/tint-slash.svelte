<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s8dze2bbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="s8dze2bbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:tint-slash" {...props}></Icon>
