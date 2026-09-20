<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g6_-33bfk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g6_-33bfk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:runtipi-light" {...props}></Icon>
