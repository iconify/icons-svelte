<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3t86dbei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v3t86dbei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:smiley-outline" {...props}></Icon>
