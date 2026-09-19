<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ctkt3ff5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ctkt3ff5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:unpin" {...props}></Icon>
