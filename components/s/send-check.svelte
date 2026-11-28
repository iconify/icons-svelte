<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rhs780b5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rhs780b5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:send-check" {...props}></Icon>
