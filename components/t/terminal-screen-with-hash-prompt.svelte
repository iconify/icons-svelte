<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ach9e5bmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ach9e5bmv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:terminal-screen-with-hash-prompt" {...props}></Icon>
