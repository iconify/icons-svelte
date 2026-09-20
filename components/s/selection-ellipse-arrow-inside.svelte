<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sy4tthbsi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sy4tthbsi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:selection-ellipse-arrow-inside" {...props}></Icon>
