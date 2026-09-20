<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cyfpfqb4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cyfpfqb4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:tooltip-edit-outline" {...props}></Icon>
