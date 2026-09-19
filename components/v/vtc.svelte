<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lcs0dxbfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lcs0dxbfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:vtc" {...props}></Icon>
