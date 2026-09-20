<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fp-r0nz9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fp-r0nz9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:toy-brick-plus-outline" {...props}></Icon>
