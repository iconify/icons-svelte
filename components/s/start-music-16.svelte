<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/anq_8t-3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="anq_8t-3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:start-music-16" {...props}></Icon>
