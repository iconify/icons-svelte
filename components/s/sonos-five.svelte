<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ob3c1xbeb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ob3c1xbeb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:sonos-five" {...props}></Icon>
