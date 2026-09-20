<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gdmajab3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="gdmajab3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:shelter-14" {...props}></Icon>
