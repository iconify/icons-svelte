<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z4dhmzbln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="z4dhmzbln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:xbp" {...props}></Icon>
