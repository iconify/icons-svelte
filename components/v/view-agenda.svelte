<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ztdnacbab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ztdnacbab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:view-agenda" {...props}></Icon>
