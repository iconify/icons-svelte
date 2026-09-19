<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hs48b569s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hs48b569s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:wind" {...props}></Icon>
