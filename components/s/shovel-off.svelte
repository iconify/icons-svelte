<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/skjw3jv2a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="skjw3jv2a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:shovel-off" {...props}></Icon>
