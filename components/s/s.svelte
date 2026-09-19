<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_gdm1jiq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":320,"height":512};
const content = `<path class="e_gdm1jiq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:s" {...props}></Icon>
