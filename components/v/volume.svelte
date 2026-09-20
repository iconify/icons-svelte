<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi6dgzbkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bi6dgzbkt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:volume" {...props}></Icon>
