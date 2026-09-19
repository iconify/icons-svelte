<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tq8bzlb8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="tq8bzlb8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:vihara" {...props}></Icon>
