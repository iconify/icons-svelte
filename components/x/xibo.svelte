<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tppqtvgwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tppqtvgwz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:xibo" {...props}></Icon>
