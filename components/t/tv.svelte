<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w5pkw1bpx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w5pkw1bpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:tv" {...props}></Icon>
