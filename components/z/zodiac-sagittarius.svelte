<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rx19rbc2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rx19rbc2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:zodiac-sagittarius" {...props}></Icon>
