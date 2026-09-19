<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zxblbxbgj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zxblbxbgj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:tractor" {...props}></Icon>
