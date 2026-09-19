<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8l9mjb4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="n8l9mjb4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:whatsapp-stroke-12" {...props}></Icon>
