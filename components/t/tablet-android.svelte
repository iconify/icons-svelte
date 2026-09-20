<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qj2r8_bif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qj2r8_bif"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:tablet-android" {...props}></Icon>
