<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xs0i7_h4h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xs0i7_h4h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:shape-polygon-add" {...props}></Icon>
