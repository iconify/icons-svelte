<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wcwryob9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="wcwryob9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:tram-stop-14" {...props}></Icon>
