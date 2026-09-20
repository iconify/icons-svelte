<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tv5n-xbeg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tv5n-xbeg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:user-md" {...props}></Icon>
