<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i1a2dm2xr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i1a2dm2xr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:vinyl-play" {...props}></Icon>
