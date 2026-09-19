<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rknujcbza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rknujcbza"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:svt-tv" {...props}></Icon>
