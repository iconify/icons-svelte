<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0cbblbuo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="m0cbblbuo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:square-web-awesome-stroke" {...props}></Icon>
