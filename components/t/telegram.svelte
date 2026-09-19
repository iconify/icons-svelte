<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ac9dv2y0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ac9dv2y0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:telegram" {...props}></Icon>
