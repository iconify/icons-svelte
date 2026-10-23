<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mhrdhkryg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mhrdhkryg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:zodiac-aquarius" {...props}></Icon>
