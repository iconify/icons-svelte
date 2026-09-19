<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mw1b57b3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mw1b57b3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:vimeo" {...props}></Icon>
