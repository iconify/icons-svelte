<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pb7i509sz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pb7i509sz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:vector-polygon" {...props}></Icon>
