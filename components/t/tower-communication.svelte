<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rzn8h_vqn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="rzn8h_vqn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:tower-communication" {...props}></Icon>
