<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vk9_32boj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="vk9_32boj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:tag-logging-filled" {...props}></Icon>
