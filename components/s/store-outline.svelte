<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tfu6ngbld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tfu6ngbld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:store-outline" {...props}></Icon>
