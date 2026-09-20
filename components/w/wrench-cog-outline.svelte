<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pm310fbzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pm310fbzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:wrench-cog-outline" {...props}></Icon>
