<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z46h88boj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z46h88boj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:storyden-light" {...props}></Icon>
