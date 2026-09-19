<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m7_n84bbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m7_n84bbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:sxm" {...props}></Icon>
