<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xxsb-cc6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xxsb-cc6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:waze" {...props}></Icon>
