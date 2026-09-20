<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hgoszjbxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hgoszjbxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:stretch-to-page-outline" {...props}></Icon>
