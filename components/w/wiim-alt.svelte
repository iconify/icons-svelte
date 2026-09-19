<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ozvh-ybic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ozvh-ybic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:wiim-alt" {...props}></Icon>
