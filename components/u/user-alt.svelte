<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_5p8ly8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z_5p8ly8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:user-alt" {...props}></Icon>
