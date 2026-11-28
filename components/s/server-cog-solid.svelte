<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pkohadzld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pkohadzld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:server-cog-solid" {...props}></Icon>
