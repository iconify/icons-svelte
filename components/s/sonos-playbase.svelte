<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ol09ncwdf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ol09ncwdf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:sonos-playbase" {...props}></Icon>
