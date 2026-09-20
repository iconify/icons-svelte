<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oiw7po6xf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oiw7po6xf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:telebugs-dark" {...props}></Icon>
