<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f92rntbkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f92rntbkt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-cyber:shrine-gate-1" {...props}></Icon>
