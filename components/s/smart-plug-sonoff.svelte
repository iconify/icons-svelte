<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gcbxedcqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gcbxedcqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:smart-plug-sonoff" {...props}></Icon>
