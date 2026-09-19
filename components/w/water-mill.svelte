<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n4mfo_b_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n4mfo_b_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:water-mill" {...props}></Icon>
