<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hlk33hjhh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hlk33hjhh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:window-open-variant" {...props}></Icon>
