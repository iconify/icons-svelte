<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m5laaqblc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="m5laaqblc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:videocam" {...props}></Icon>
