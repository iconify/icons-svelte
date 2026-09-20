<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f42v76bcy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f42v76bcy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:unlock-sharp" {...props}></Icon>
