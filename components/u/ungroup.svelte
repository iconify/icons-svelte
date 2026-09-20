<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e32vr12xd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e32vr12xd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:ungroup" {...props}></Icon>
