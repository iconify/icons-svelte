<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tmsss6jrd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tmsss6jrd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:skysports-f1" {...props}></Icon>
