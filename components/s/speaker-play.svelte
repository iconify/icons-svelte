<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rzl4o-zjc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rzl4o-zjc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:speaker-play" {...props}></Icon>
