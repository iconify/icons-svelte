<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-1y4eb2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x-1y4eb2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:text-align-left" {...props}></Icon>
