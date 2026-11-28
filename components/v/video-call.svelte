<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g2p-_v4fw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g2p-_v4fw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:video-call" {...props}></Icon>
