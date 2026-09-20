<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ew6x_87ns.css';
import '../../css/l/lfj5m2b1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ew6x_87ns"/><path class="lfj5m2b1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:whatsapp" {...props}></Icon>
