<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/clgzsub0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="clgzsub0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:user-cog-20-bold" {...props}></Icon>
