<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vfptfslfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vfptfslfy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:wave-arrow-up" {...props}></Icon>
