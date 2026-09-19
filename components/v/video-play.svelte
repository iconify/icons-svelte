<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/istk9mqfb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="istk9mqfb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:video-play" {...props}></Icon>
