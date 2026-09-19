<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/htej5lsdf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="htej5lsdf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:wilted-flower" {...props}></Icon>
