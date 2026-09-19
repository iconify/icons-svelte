<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rzkmj9bfa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rzkmj9bfa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:wand" {...props}></Icon>
