<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zlr8r5bfe.css';
import '../../css/y/yt28hwmoe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zlr8r5bfe"/><path class="yt28hwmoe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:text-color-fill-16" {...props}></Icon>
