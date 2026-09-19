<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ms7rf3bcm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="ms7rf3bcm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:shuttle-space" {...props}></Icon>
