<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z2tu_cbaa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="z2tu_cbaa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:ruble-sign-solid" {...props}></Icon>
