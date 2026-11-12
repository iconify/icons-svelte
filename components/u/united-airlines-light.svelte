<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s0s5asbdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s0s5asbdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:united-airlines-light" {...props}></Icon>
