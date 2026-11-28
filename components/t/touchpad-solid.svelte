<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/esleaibty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="esleaibty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:touchpad-solid" {...props}></Icon>
