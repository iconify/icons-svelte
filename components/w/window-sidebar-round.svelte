<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0kebbvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jx0kebbvc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:window-sidebar-round" {...props}></Icon>
