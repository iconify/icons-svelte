<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ra1_58_jv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ra1_58_jv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:square-solid" {...props}></Icon>
