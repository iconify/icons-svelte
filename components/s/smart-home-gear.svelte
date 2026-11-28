<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yi1q-lbdp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yi1q-lbdp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:smart-home-gear" {...props}></Icon>
