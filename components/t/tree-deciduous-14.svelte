<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y5y513utc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="y5y513utc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:tree-deciduous-14" {...props}></Icon>
