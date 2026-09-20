<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-s8rx_ul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m-s8rx_ul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:subtitles" {...props}></Icon>
