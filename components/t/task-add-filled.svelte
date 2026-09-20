<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_hxwwbci.css';
import '../../css/d/dpnipcczy.css';
import '../../css/p/poiuuuhna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h_hxwwbci"/><path class="dpnipcczy"/><path class="poiuuuhna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:task-add-filled" {...props}></Icon>
