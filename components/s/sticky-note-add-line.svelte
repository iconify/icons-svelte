<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oaijq3vgm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oaijq3vgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:sticky-note-add-line" {...props}></Icon>
