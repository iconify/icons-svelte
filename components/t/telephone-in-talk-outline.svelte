<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h0b83e9ne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h0b83e9ne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:telephone-in-talk-outline" {...props}></Icon>
