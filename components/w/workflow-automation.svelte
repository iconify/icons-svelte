<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/auo3ycdia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="auo3ycdia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:workflow-automation" {...props}></Icon>
