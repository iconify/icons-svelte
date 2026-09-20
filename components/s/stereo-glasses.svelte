<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uskxbbb4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uskxbbb4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:stereo-glasses" {...props}></Icon>
