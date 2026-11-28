<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u9xkg9b0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u9xkg9b0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:sidebar-x" {...props}></Icon>
