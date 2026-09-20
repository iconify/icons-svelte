<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y29r7jb_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y29r7jb_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:stomach" {...props}></Icon>
