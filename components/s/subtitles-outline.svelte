<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mh7ffuh6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mh7ffuh6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:subtitles-outline" {...props}></Icon>
