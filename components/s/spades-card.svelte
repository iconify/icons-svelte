<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pv0hedcfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="pv0hedcfd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:spades-card" {...props}></Icon>
