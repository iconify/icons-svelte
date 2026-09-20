<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r8mngo21a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="r8mngo21a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="quill:search" {...props}></Icon>
