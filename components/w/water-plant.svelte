<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/by7szym1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="by7szym1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:water-plant" {...props}></Icon>
