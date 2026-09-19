<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rfhg5ym_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rfhg5ym_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:touch" {...props}></Icon>
