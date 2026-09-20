<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g4tjj3_pn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g4tjj3_pn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:shop-complete" {...props}></Icon>
