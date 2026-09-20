<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sw5vo3fbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="sw5vo3fbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:wheelchair-1" {...props}></Icon>
