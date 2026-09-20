<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9b9j0bzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n9b9j0bzf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:view-module-outline" {...props}></Icon>
