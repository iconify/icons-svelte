<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lzoallehr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lzoallehr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:user-sparkle-corner-round" {...props}></Icon>
