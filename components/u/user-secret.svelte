<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u0n02obus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="u0n02obus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:user-secret" {...props}></Icon>
