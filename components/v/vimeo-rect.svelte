<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxoo9ox9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1000,"height":1000};
const content = `<path class="fxoo9ox9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="brandico:vimeo-rect" {...props}></Icon>
