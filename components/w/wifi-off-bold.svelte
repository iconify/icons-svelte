<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pgnn-dbdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pgnn-dbdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:wifi-off-bold" {...props}></Icon>
