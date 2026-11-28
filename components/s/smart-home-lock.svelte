<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tgnjzj3hk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tgnjzj3hk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:smart-home-lock" {...props}></Icon>
