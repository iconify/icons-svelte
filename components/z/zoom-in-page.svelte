<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x33363h0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x33363h0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:zoom-in-page" {...props}></Icon>
