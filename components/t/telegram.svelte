<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mb_1p-bgl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mb_1p-bgl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:telegram" {...props}></Icon>
