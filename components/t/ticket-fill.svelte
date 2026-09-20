<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c00g-56-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c00g-56-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:ticket-fill" {...props}></Icon>
