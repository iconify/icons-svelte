<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fs4k7ccaa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="fs4k7ccaa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:strikethrough" {...props}></Icon>
