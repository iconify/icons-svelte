<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gg7yu4bmq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gg7yu4bmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:sonos-play-3" {...props}></Icon>
