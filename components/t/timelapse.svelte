<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nhl-ulblf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nhl-ulblf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:timelapse" {...props}></Icon>
