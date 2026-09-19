<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-0fabb_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z-0fabb_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:terminal-circle-filled" {...props}></Icon>
