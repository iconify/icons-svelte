<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/afsz9ac8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="afsz9ac8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:terminal-screen-with-percent-prompt" {...props}></Icon>
