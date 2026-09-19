<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qpop9977l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qpop9977l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:sonos-sub-mini" {...props}></Icon>
