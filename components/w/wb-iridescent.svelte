<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a4x3cd_oo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":368,"height":472};
const content = `<path class="a4x3cd_oo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:wb-iridescent" {...props}></Icon>
