<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/urv1w5b0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="urv1w5b0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:scan-sparkle-round" {...props}></Icon>
