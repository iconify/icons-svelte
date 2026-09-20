<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/ws2pigb1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ws2pigb1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:victron-energy" {...props}></Icon>
