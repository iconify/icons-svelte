<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ueh3k2czz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ueh3k2czz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:track-next" {...props}></Icon>
