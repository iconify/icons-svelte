<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ju1iq-4lb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ju1iq-4lb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:youtube-fill-round" {...props}></Icon>
