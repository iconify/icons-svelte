<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mz8xdsbdv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":464,"height":488};
const content = `<path class="mz8xdsbdv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:yahoo-messenger" {...props}></Icon>
