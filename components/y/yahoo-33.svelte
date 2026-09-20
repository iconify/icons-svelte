<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ihf03qhvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="ihf03qhvk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:yahoo-33" {...props}></Icon>
