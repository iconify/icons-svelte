<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kgpq7zwwr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kgpq7zwwr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:webcam-round" {...props}></Icon>
