<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xsym9qk0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xsym9qk0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:sonos-sub" {...props}></Icon>
