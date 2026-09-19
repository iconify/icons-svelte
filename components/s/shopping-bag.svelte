<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rwq5dfatl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rwq5dfatl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:shopping-bag" {...props}></Icon>
