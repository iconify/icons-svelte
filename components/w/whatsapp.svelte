<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ka84vzb2a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="ka84vzb2a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:whatsapp" {...props}></Icon>
