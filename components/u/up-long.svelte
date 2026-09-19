<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y8ug4ybrq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":320,"height":512};
const content = `<path class="y8ug4ybrq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:up-long" {...props}></Icon>
