<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uup_hebcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uup_hebcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:tooltip-image-outline" {...props}></Icon>
