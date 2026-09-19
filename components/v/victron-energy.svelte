<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xupgi1b6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xupgi1b6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:victron-energy" {...props}></Icon>
