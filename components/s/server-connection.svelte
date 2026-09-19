<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u14wlwbax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u14wlwbax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:server-connection" {...props}></Icon>
