<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j0jiv0brb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j0jiv0brb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:timeline-help-outline" {...props}></Icon>
