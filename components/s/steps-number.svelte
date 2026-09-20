<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r3f20yb_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r3f20yb_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:steps-number" {...props}></Icon>
