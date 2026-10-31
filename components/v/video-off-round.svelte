<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uyaubwshj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uyaubwshj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:video-off-round" {...props}></Icon>
