<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kgcm7abof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kgcm7abof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:usps" {...props}></Icon>
