<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxle2tv-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":464,"height":448};
const content = `<path class="fxle2tv-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:slideshare" {...props}></Icon>
