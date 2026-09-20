<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pgij2qbdv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pgij2qbdv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:star-half-alt" {...props}></Icon>
