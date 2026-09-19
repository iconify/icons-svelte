<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wakedjb-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wakedjb-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:wall-inara" {...props}></Icon>
