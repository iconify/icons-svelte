<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rg3v8jk9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rg3v8jk9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:yahoo-light" {...props}></Icon>
