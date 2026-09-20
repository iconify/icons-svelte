<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bymhd4bfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bymhd4bfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:skull-solid" {...props}></Icon>
