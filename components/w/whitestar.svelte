<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s6nv3mz1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s6nv3mz1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:whitestar" {...props}></Icon>
