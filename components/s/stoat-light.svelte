<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m1c76acum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m1c76acum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:stoat-light" {...props}></Icon>
