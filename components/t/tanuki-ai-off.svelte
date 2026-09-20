<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/am92l0d3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="am92l0d3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:tanuki-ai-off" {...props}></Icon>
