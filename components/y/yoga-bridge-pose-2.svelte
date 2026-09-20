<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwg6iibbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wwg6iibbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:yoga-bridge-pose-2" {...props}></Icon>
