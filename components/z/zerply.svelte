<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rz_2ei_9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":336,"height":488};
const content = `<path class="rz_2ei_9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:zerply" {...props}></Icon>
