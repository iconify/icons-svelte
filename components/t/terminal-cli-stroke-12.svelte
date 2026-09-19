<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g2dxccp7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="g2dxccp7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:terminal-cli-stroke-12" {...props}></Icon>
