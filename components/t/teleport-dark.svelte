<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_294hbia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t_294hbia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:teleport-dark" {...props}></Icon>
