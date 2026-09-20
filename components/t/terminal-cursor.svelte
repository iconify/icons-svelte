<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yq8o9f3-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yq8o9f3-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:terminal-cursor" {...props}></Icon>
