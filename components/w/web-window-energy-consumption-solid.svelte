<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/czc8w0x3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="czc8w0x3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:web-window-energy-consumption-solid" {...props}></Icon>
