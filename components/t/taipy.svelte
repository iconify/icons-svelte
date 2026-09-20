<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wgq2g6byn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wgq2g6byn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:taipy" {...props}></Icon>
