<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uj4i3hkdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uj4i3hkdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:ubt" {...props}></Icon>
